# Horizon
[![Build Status](https://travis-ci.org/stellar/go.svg?branch=master)](https://travis-ci.org/stellar/go)

Horizon is the client facing API server for the [Stellar ecosystem](https://www.stellar.org/developers/guides/get-started/).  It acts as the interface between [Stellar Core](https://www.stellar.org/developers/stellar-core/software/admin.html) and applications that want to access the Stellar network. It allows you to submit transactions to the network, check the status of accounts, subscribe to event streams and more.

## Try it out
See Horizon in action by running your own Stellar node as part of the Stellar [testnet](https://www.stellar.org/developers/guides/concepts/test-net.html). With our Docker quick-start image, you can be running your own fully functional node in around 15 minutes. See the [quickstart](internal/docs/quickstart) guide to get up and running.

## Run a production server
If you're an administrator planning to run a production instance of Horizon as part of the public Stellar network, check out our detailed [administration guide](internal/docs/administration). It covers installation, monitoring, error scenarios and more.

## Contributing
As an open source project, development of Horizon is public, and you can help! We welcome new issue reports, documentation and bug fixes, and contributions that further the project roadmap. Our [development guide](internal/docs/development) will show you how to build Horizon, see what's going on behind the scenes, and set up an effective develop-test-push cycle so that you can get your work incorporated quickly.
