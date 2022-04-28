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

All of the above, expect last command

```
coinman --testnet runserver

```

`
