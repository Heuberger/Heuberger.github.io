# Certificates

Certificates used to validate applications of this  [organization](https://heuberger.github.io/) so these can be started using Java Web Start.

## Installing

- download the keys and the install script:
  - [cfhca.cer](https://heuberger.github.io/keys/cfhca.cer) - Root Authority certificate
  - [cfhsi.cer](https://heuberger.github.io/keys/cfhsi.cer) - Code signer certificate, installed as trusted certificate to suppress warnings
  - [install-cert.cmd](https://heuberger.github.io/keys/install-cert.cmd) - install certificates for Windows

- execute `install-cert.cmd` as administrator - right-click and select `Run as Administrator`
- oprional/alternative: use `certmgr.msc` to check that both certificates are installed or to install the certificates:
  - `CFH Root CA` listed under `Trusted Root Certificates`
  - `CFH Signature` listed under `Trusted Publishers`



