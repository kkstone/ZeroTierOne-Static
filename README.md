# ZeroTier-One static binaries
This project provides static [Zerotier-One](https://github.com/zerotier/ZeroTierOne) binaries.

# Installing
*To install ZeroTier-One on Steam Deck you can follow: [Steam Deck (SteamOS 3)](SteamDeck.md)*

Download latest release:
```sh
curl -LJO https://github.com/kkstone/ZeroTierOne-Static/releases/latest/download/zerotier-one-x86_64.tar.gz
```

And install it to bin:
```sh
tar -xzf zerotier-one-x86_64.tar.gz
install bin/* /bin
```
# Building
To build latest version run:
```sh
make
```
To build specific version, set variable:
```sh
make ZT_VERSION=1.14.2
```
