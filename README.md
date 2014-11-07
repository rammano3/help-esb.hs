help-esb.hs
===========

A Haskell client for our ESB.

## Installation
1. Install the [haskell-platform](https://www.haskell.org/platform).
2. `cabal install missingh`
3. `cabal install aeson`
4. Import `HelpEsbClient` into your microservice and go!

## examples/basic.hs
Included is a [basic implementation](examples/basic.hs) that simply logs into the ESB, verifies the login,
then listens and logs out raw input from its subscriptions.

To run it for yourself do:

1. `cd examples`
2. `ghc -i../ basic.hs`
3. `./basic`
