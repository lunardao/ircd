# IRCD Setup

For the purpose of a quick and instant chat or communication which is 100% anonymous and if chosen private, we use [ircd](https://darkrenaissan    ce.github.io/darkfi/misc/ircd/ircd.html) - a peer-to-peer chat, built by [DarkFi]((https://dark.fi). 

* The ircd source: https://github.com/darkrenaissance/darkfi/tree/master/bin/ircd
* Weechat documentation: https://weechat.org/doc/

## Installation

**Dependencies**

```sh
sudo apt-get install -y git make jq gcc weechat pkg-config libssl-dev
```
On debian based system, the user can run this to install dependencies:

```sh
sudo apt-get update
```
```sh
sudo apt-get install -y git make jq gcc weechat pkg-config libmpg123-dev
```
For other os, check [here](https://darkrenaissance.github.io/darkfi/index.html) to see which dependencies are needed. 

### ircd

We are working on binaries for different systems and will share them soon here. To install ircd, and setup the chat client [Weechat](https://weechat.org/files/doc/stable/weechat_user.en.html) follow DarkFi's [ircd installation guide](https://darkrenaissance.github.io/darkfi/misc/ircd/ircd.html).

