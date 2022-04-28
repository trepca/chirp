# Chirp

A messaging protocol.

Features

- broadcasting to everyone
- group channels.

![Image](/chirp.png "Chirp - messaging dApp")

# Quickstart with a simulator

No requirements, no nodes running etc.

```sh
git clone git@github.com:trepca/coinman.git
poetry install
poetry shell

```

Clone Chirp, a messaging protocol, that includes UX too.

```
git clone git@github.com:trepca/chirp.git`

cd chirp

coinman init .

# run it in a  simulator

coinman --simulator runserver



```

# Running on testnet or mainnet

You'll need a full node for testnet or mainnet and chia config file the machine you're running this.

Install coinman as before and run poetry shell.

```
git clone git@github.com:trepca/chirp.git`

cd chirp
# for testnet
coinman init --testnet .

# for mainnet
coinman init .


coinman runserver



```
