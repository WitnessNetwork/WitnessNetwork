# WitnessNetwork

Witness Network (WNET), a data wormhole between blockchains and the reality. 
WNET is one of Hubs of Cosmos, just like Cosmos Hub and IRISNET.
The officail website is located at https://WitnessNetwork.com 

## 1 Application Schemes

(1). Smart contracts need data from outside of blockchain, such as traditional websites, cloud or software systems.  

(2). Under the cross-chain scheme, one blockchain should know certain data from the other one's. 

## 2 Creative Technologies

(1).  To replace a single or centralized oracle with a decentralized and consensus-based blockchain network;

(2). To ensure the trustworthiness of data sources by multi-nodes and multi-data sources;

(3). The consensus mechanism  make sure the credibility of the on-chain data;

(4). Data from traditional websites are stored on blockchain and never lost.

(5). Based on cosmos, it is easy to develop on Witness Network, and the stored data could be used by many blockchains.

[![CircleCI](https://circleci.com/gh/cosmos/gaia/tree/master.svg?style=shield)](https://circleci.com/gh/cosmos/gaia/tree/master)
[![codecov](https://codecov.io/gh/cosmos/gaia/branch/master/graph/badge.svg)](https://codecov.io/gh/cosmos/gaia)
[![Go Report Card](https://goreportcard.com/badge/github.com/cosmos/gaia)](https://goreportcard.com/report/github.com/cosmos/gaia)
[![license](https://img.shields.io/github/license/cosmos/gaia.svg)](https://github.com/cosmos/gaia/blob/master/LICENSE)
[![LoC](https://tokei.rs/b1/github/cosmos/gaia)](https://github.com/cosmos/gaia)
[![GolangCI](https://golangci.com/badges/github.com/cosmos/gaia.svg)](https://golangci.com/r/github.com/cosmos/gaia)
[![riot.im](https://img.shields.io/badge/riot.im-JOIN%20CHAT-green.svg)](https://riot.im/app/#/room/#cosmos-sdk:matrix.org)

This repository hosts `WitnessNetwork`, based on the Cosmos Hub.

**Note**: Requires [Go 1.12+](https://golang.org/dl/)

**DISCLAIMER**: The current version of Gaia running the Cosmos Hub (v0.34.x) is
__NOT__ maintained in this repository. Gaia and the [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/)
have been recently split. All future versions of Gaia, including the next major
upgrade, will be maintained in this repository. However, until the next major upgrade,
Gaia should be fetched and built from the latest [released](https://github.com/cosmos/cosmos-sdk/releases)
__v0.34.x__ version in the SDK repository. In addition, this repository should be
considered unstable until the next major release of Gaia. Please bear with us
while we continue the migration process and update documentation.

## WitnessNetwork Hub Mainnet

To run a full-node for the mainnet of the Cosmos Hub, first [install `wnet`](./docs/installation.md), then follow [the guide](./docs/join-mainnet.md).

For status updates and genesis file, see the [launch repo](https://github.com/WitnessNetwork/launch).

## Quick Start

```
make install
```

## Disambiguation

This Cosmos-SDK project is not related to the [React-Cosmos](https://github.com/react-cosmos/react-cosmos) project (yet). Many thanks to Evan Coury and Ovidiu (@skidding) for this Github organization name. As per our agreement, this disambiguation notice will stay here.


