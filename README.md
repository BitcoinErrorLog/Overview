# Overview

The Bitcoin And Lightning Layer Specs (BALLS) are a set of specifications for software key managers ("wallets") that use Bitcoin and Lighting Network payment concepts to interact with websites.

A common convention in the Bitcoin web application ecosystem is for wallets to expose their API via a JavaScript object in the web page. This object is called the common web wallet interface.

Historically, provider implementations have exhibited conflicting interfaces and behaviors between wallets. This working group formalizes a Bitcoin extension API to promote wallet interoperability. The API is designed to be minimal, event-driven, and agnostic of transport and RPC protocols. Its functionality is easily extended by defining new RPC methods and message event types.

Historically, implementations have been made available as window.bitcoin in web browsers, but this convention is not part of the specification.

A list of current work in progress can be tracked from the [issues](https://github.com/BitcoinAndLightningLayerSpecs/playground/issues) tab in the [playground repository](https://github.com/BitcoinAndLightningLayerSpecs/playground/issues), which includes a functional spec demonstration.

For more information, anyone can join our chat group in Telegram at https://t.me/bitcoinandlightningspecs

Current apps aiming to support BALLS:
- [Alby](https://getalby.com/)
- [unreleased wallet by Synonym](https://synonym.to)
