# cobo-vault-system
Cobo Vault is an air-gapped, open source hardware wallet that uses completely transparent QR code data transmissions. Visit the [Cobo Vault official website]( https://cobo.com/hardware-wallet/cobo-vault)  to learn more about Cobo Vault.

You can also follow [@Cobo Vault](https://twitter.com/CoboVault) on Twitter.

<div align=center><img src="https://cobo.com/_next/static/images/intro-2b5b0b44cc64639df4fcdd9ccc46fd4b.png"/></div>

## Contents

- [Introduction](#introduction)
- [Clone](#clone)
- [Build](#build)
- [Test](#test)
- [Code Structure](#code-structure)
- [Core Dependencies](#core-dependencies)
- [Issues and PRs](#issues-and-prs)
- [License](#license)


## Introduction
Cobo Vault runs as a standalone application on customized hardware and Android 8.1 Oreo (Go Edition). 

## Clone

    git clone git@github.com:CoboVault/cobo-vault-system.git

## Build


## Code Structure
Modules

`app`: Main application module

`coinlib`: Module for supported blockchains, currently included in 12 blockchains

`encryption-core`: Module for the Secure Element, includes commands, protocol, serialize/deserialize, serial port communication

## Core Dependencies

## Issues and PRs
Please submit any issues [here](https://github.com/CoboVault/cobo-vault-system/issues). PRs are also welcome!

## License
See the [LICENSE](LICENSE) file for details.
