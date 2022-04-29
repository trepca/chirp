# Chirp

A messaging app running on Chia blockchain.

## Features

- send messages to general channel
- send messages to a group 
- send messages to a public key
- anonymous and censorship resistant messaging  
- web UI
- fee handling 

Runs on [Coinman](https://github.com/trepca/coinman)


And here's a screenshot: 

![Image](/chirp.png "Chirp - messaging dApp")

# Quickstart with a simulator

No external service requirements, no nodes running etc.

Install poetry if you don't have it already: 
https://python-poetry.org/docs/master/#installing-with-the-official-installer

Install [coinman](https://github.com/trepca/coinman):

```
git clone git@github.com:trepca/coinman.git

poetry install

poetry shell

```

Now you can install Chirp.

```
git clone git@github.com:trepca/chirp.git

cd chirp

coinman init .

# run it in a simulator

coinman --simulator runserver
```

# Running on testnet or mainnet

You'll need a full node for testnet or mainnet and chia config file the machine you're running this.

Install coinman as before and run poetry shell.

```
git clone git@github.com:trepca/chirp.git

cd chirp
# for testnet
coinman init --testnet .

# for mainnet
coinman init .


coinman runserver



```
