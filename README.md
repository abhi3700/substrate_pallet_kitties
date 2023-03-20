# substrate_pallet_kitties

Kitties Pallet for a Substrate chain

## Overview

- Kitties pallet provides functionality for:
  - 😺 Be created either by some original source or by being bred using existing Kitties.
  - 😼 Be sold at a price set by their owner.
  - 😿 Be transferred from one owner to another.
- [ ] <u>Future scope</u>:
  - Writing tests for our pallet.
  - Declaring a configuration for the genesis of our chain.
  - Customize frontend for our Substrate Kitties.

## Procedure

1. **Basic setup**: We'll need to spin up a Substrate node and create a custom pallet
2. **Runtime storage**: We'll need a total of 9 storage items in our pallet to keep track of the amount of Kitties; their index; their owners and their owner account IDs.
3. **Dispatchable functions**: We'll need a total of 5 dispatchable functions: `create`, `set_price`, `transfer`, `buy_kitty` and `breed_kitty`
4. **Private functions**: We'll write 2 helper functions to handle randomness: `increment_nonce` and `random_hash`
5. **Helper functions**: We'll write 2 helper functions for our dispatchable functions: `mint` and `transfer_from`.

## Installation

<!-- TODO: -->

## Build

<!-- TODO: -->

## Unit Test

<!-- TODO: -->

## Summary

<!-- TODO: -->

## References

1. [Overview](https://learn.figment.io/tutorials/substrate-kitties-overview)
2. [Setup - Part I](https://learn.figment.io/tutorials/substrate-kitties-setup)
3. [Create Kitties - Part II: Uniqueness, custom types and storage maps](https://learn.figment.io/tutorials/substrate-kitties-create-kitties)
4. [Dispatchables & Events - Part III](https://learn.figment.io/tutorials/substrate-kitties-dispatchables-and-events)
5. [Interacting with your Kitties - Part IV](https://learn.figment.io/tutorials/substrate-kitties-interacting-functions)
