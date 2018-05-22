Pptp Core 0.12.2.4
=====================

This is the official reference wallet for Pptp digital currency and comprises the backbone of the Pptp peer-to-peer network. You can [download Pptp Core](https://github.com/conan-equal-newone/pptp/releases) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run Pptp on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/pptp-qt` (GUI) or
- `bin/pptpd` (headless)

### Windows

Unpack the files into a directory, and then run pptp-qt.exe.

### OS X

Drag Pptp-Qt to your applications folder, and then run Pptp-Qt.

### Need Help?

* See the [Pptp documentation](https://github.com/conan-equal-newone/pptp/tree/master/doc)
for help and more information.
* Ask for help on [PPTP Discord channel](https://discord.gg/*).
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=*) forums.

Building
---------------------
The following are developer notes on how to build Pptp Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Pptp Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [BitcointalkTalk](https://bitcointalk.org/index.php?topic=3146751) forums.
* Discuss on [PPTP Discord channel](https://discord.gg/6vGNAh5).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
