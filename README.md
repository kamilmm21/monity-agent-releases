# Monity server agent: releases

Signed packages and the installer of the Monity server agent ([monity.ai](https://monity.ai)). The source is not here.

Install on a Linux server (x86_64; Debian, Ubuntu, Amazon Linux, RHEL and its relatives):

    curl -fsSL https://github.com/kamilmm21/monity-agent-releases/releases/latest/download/install.sh | sudo sh

The installer checks `SHA256SUMS.sig` with Monity's release key before it trusts any file, checks every file against
`SHA256SUMS`, and checks the agents' root certificate by its fingerprint. It starts nothing. Then add the server on
monity.ai › Server › Add a server.
