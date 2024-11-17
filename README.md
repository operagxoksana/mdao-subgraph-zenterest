# ZENTREST-subgraph

Deployed to https://thegraph.com/explorer/subgraph/spaceforce-dev/zen-prelim-v001

Subgraph endpoints:
Queries (HTTP): https://api.thegraph.com/subgraphs/name/spaceforce-dev/zen-prelim-v001
Subscriptions (WS): wss://api.thegraph.com/subgraphs/name/spaceforce-dev/zen-prelim-v001

[Zentrest](https://app.mantradao.com/) is an open-source protocol for algorithmic, efficient Money Markets on the Ethereum blockchain. This Subgraph ingests the V2 contracts of the protocol.

this Subgraph is forked from Compounds subgraph implementation

### ABI

The ABI used is `ctoken.json`. It is a stripped down version of the full abi provided by compound, that satisfies the calls we need to make for both cETH and cERC20 contracts. This way we can use 1 ABI file, and one mapping for cETH and cERC20.

## Getting started with querying

Below are a few ways to show how to query the Compound V2 Subgraph for data. The queries show most of the information that is queryable, but there are many other filtering options that can be used, just check out the [querying api](https://github.com/graphprotocol/graph-node/blob/master/docs/graphman-graphql-api.md).

You can also see the saved queries on the hosted service for examples.
