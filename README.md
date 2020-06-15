# cobo-vault-system
Cobo Vault is an air-gapped, open source hardware wallet that uses completely transparent QR code data transmissions. Visit the [Cobo Vault official website]( https://cobo.com/hardware-wallet/cobo-vault)  to learn more about Cobo Vault.

You can also follow [@Cobo Vault](https://twitter.com/CoboVault) on Twitter.

<div align=center><img src="https://cobo.com/_next/static/images/intro-2b5b0b44cc64639df4fcdd9ccc46fd4b.png"/></div>

## Contents

- [Introduction](#introduction)
- [Issues and PRs](#issues-and-prs)
- [License](#license)


## Introduction
Cobo Vault runs as a standalone application on customized hardware and Android 8.1 Oreo (Go Edition).
This repo contains the Android system code. From the code you can clearly see how we did the following to customize the Android system and minimize the attack surface:
- Closing adb and remove adb daemon
- Removing system processes/apps
- Preventing installation of third-party apps
- Patching Linux Kernel vulnerabilities

Also we took full advantage of security features inherent in Android like Full-Disk Encryption, TEE, Verified Boot, and SELinux.
Due to copyright, some vendors’ code cannot be made public, and we have removed some of the code from the source code.
Therefore this open source code cannot be compiled. However, we can share this part of code under an NDA if you want to fully verify the code and reproduce it. Please send an email to cobovault@cobo.com.
Since the size of a single repo on github cannot exceed 5G, we put the code on AWS. You can access the code through this link:
[cobo-vault-system](https://cobo-vault-system)


## Issues and PRs
Please submit any issues [here](https://github.com/CoboVault/cobo-vault-system/issues). PRs are also welcome!

## License
See the [LICENSE](LICENSE) file for details.
