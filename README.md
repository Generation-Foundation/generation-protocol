## Generation Protocol

Official Ethereum-compatible Blockchain Networks of the Generation Protocol. To find out more about Generation, visit the [official website](https://gen.foundation/).

WARNING: This is a work in progress so architectural changes may happen in the future.

## Building the source

Building `geth` requires both a Go (version 1.16 or later) and a C compiler. You can install
them using your favourite package manager. Once the dependencies are installed, run

```shell
make geth
```

or, to build the full suite of utilities:

```shell
make all
```

## Running an Endpoint Node

Endpoint Node is an entry point from the outside of the network in order to
interact with the Generation protocol. Currently, an official networks are available: **generation-leo** (testnet).