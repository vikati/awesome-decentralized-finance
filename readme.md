# Awesome Open Finance  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/jtoy/awesome)

A curated list of awesome open finance projects, software, and resources.  

## What is Open Finance?

Open finance is the movement that leverages open source software and decentralized networks to transform traditional financial products into trustless and transparent protocols that operate without unnecessary intermediaries.  One could envision open finance impacting the financial world the same way that open source software has changed software products.

## Table of Contents

- [Decentralized Exchange Protocols](#decentralized-exchange-protocols)
- [Stablecoins](#stablecoins)
- [Lending Protocols](#lending-protocols)
- [Derivative Protocols/Prediction Markets](#derivative-protocols)
- [Bundling Protocols](#bundling-protocols)
- [Tokenization Protocols](#tokenization-protocols)
- [Fund Protocols](#fund-protocols)
- [Misc](#misc)
- [Community](#community)

<a name="decentralized-exchange-protocols" />

## Decentralized Exchange Protocols

- [BitShares](https://bitshares.org/technology/decentralized-asset-exchange/) ([source code](https://github.com/bitshares), [white paper](https://www.bitshares.foundation/papers/BitSharesBlockchain.pdf)) - Decentralized exchange protocol based on the Graphene blockchain
- Bitcoin
  - [Bisq](https://bisq.network) ([source code](https://github.com/bisq-network/bisq), [white paper](https://github.com/bisq-network/bisq-docs/blob/master/exchange/whitepaper.adoc)) - Protocol for peer-to-peer exchange of bitcoin
- Ethereum
  - [0x](https://0xproject.com) ([source code](https://github.com/0xProject), [white paper](https://0xproject.com/pdfs/0x_white_paper.pdf)) - Protocol for decentralized exchange of Ethereum assets using relayers, now on version 2
  - [Bancor Protocol](https://about.bancor.network/protocol/) ([source code](https://github.com/bancorprotocol/contracts), [white paper](https://storage.googleapis.com/website-bancor/2018/04/01ba8253-bancor_protocol_whitepaper_en.pdf)) - Protocol for converting one token to another using "smart tokens"
  - [Hydro](https://thehydrofoundation.com/) ([white paper](https://thehydrofoundation.com/Hydro-Whitepaper-v0116-en.pdf)) -  Protocol for "high performance decentralized exchanges and marketplaces with built-in incentives for coordination"
  - [Kyber](https://kyber.network) ([source code](https://github.com/kybernetwork), original white paper removed from website but is archived [here](https://whitepaper.io/document/43/kyber-network-whitepaper)) - On-chain protocol for decentralized token swaps and for easy application integration
  - [Republic](https://republicprotocol.com) ([source code](https://republicprotocol.com), [white paper](https://releases.republicprotocol.com/whitepaper/1.0.0/whitepaper_1.0.0.pdf)) - Decentralized dark pool protocol for atomic swaps of digital assets
  - [Swap / AirSwap's Protocol](https://airswap.io) ([source code](https://github.com/airswap), [white paper](https://swap.tech/whitepaper/)) - Protocol for peer-to-peer trading of ERC20 tokens

- [Stellar](https://www.stellar.org/developers/guides/concepts/exchange.html) ([source code](https://github.com/stellar)) - Decentralized protocol for financial applications, including support for decentralized exchange
  

<a name="stablecoins" />

## Stablecoins

- IOU / Centralized
  - Bitcoin / Omni
    - [Tether](https://tether.to) (closed source, [white paper](https://tether.to/wp-content/uploads/2016/06/TetherWhitePaper.pdf)) - Controversial USD-backed token connected to Bitfinex
  - Ethereum
    - [Circle USDC](https://www.circle.com/en/usdc) ([source code](https://github.com/centrehq), [white paper](https://www.centre.io/pdfs/centre-whitepaper.pdf)) - ERC-20 stablecoin issued by Circle
    - [Gemini Dollar](https://gemini.com/dollar/) ([source code](https://github.com/gemini/dollar), [white paper](https://gemini.com/wp-content/themes/gemini/assets/img/dollar/gemini-dollar-whitepaper.pdf)) - ERC-20 stablecoin issued by Gemini
    - [Paxos](https://www.paxos.com/standard/) ([source code](https://github.com/paxosglobal/pax-contracts), [white paper](https://www.paxos.com/wp-content/uploads/2018/10/PAX-Whitepaper.pdf)) - ERC-20 stablecoin issued by Paxos Trust Company
    - [TrueUSD](https://www.trusttoken.com/trueusd/) ([source code](https://github.com/trusttoken/trueUSD)) - ERC-20 stablecoin with KYC/AML issued by TrustToken
- Collateralized
  - [Celo](https://celo.org) - Over-collateralized stablecoin targeting the unbanked using its own distributed ledger
  - Ethereum
    - [Dai Stablecoin from Maker](https://makerdao.com/dai) ([source code](https://github.com/makerdao), [white paper](https://makerdao.com/whitepaper/)) - Stablecoin based on smart contracts for creating collateralized debt positions
    - [Havven](https://havven.io/)([source code](https://github.com/Havven/havven), [white paper](https://havven.io/uploads/havven_whitepaper.pdf)) - Decentralized stablecoin modeled on centralized closed loop payment networks
- Algorithmic
  - Ethereum
    - [Basis](https://www.basis.io) ([white paper](https://www.basis.io/basis_whitepaper_en.pdf)) - Algorithmic stablecoin that "can be robustly pegged to arbitrary assets or baskets of goods"
    - [Carbon](https://fiat.carbon.money) ([white paper](https://www.carbon.money/whitepaper.pdf))  - Stablecoin that will be composed of a basket of whitelisted tokens that is "functionally fiat-backed with the potential to whitelist an algorithmic stablecoin" 
    - [Fragments](https://www.fragments.org) ([white paper](https://www.fragments.org/paper/)) - Monetary policy-based stablecoin protocol

<a name="lending-protocols" />

## Lending Protocols

- Ethereum
  - [Compound](http://compound.finance) ([source code](https://github.com/compound-finance/), [white paper](https://compound.finance/documents/Compound.Whitepaper.v04-83de48b6622ddd665234b41076d04c8b.pdf?vsn=d)) - Protocol for algorithmic money markets
  - [Dharma](https://dharma.io) ([source code](https://github.com/dharmaprotocol), [white paper](https://whitepaper.dharma.io)) - Protocol for building lending products using tokenized debt
  - [Ethlend](http://ethlend.io) ([source code](https://github.com/ETHLend), [white paper](https://github.com/ETHLend/Documentation/blob/master/ETHLendWhitePaper.md)) - Marketplace for peer-to-peer lending
  - [Lendroid](https://www.lendroid.com) ([source code](https://github.com/lendroidproject), [white paper](https://uploads-ssl.webflow.com/5b3d0e23faf03c5dc943df64/5b3d0e23faf03c96e243df86_whitepaper-margin-trading-2-18.pdf)) - Protocol for decentralized lending, margin trading, and short selling
  - [Marble](https://marble.org) ([source code](https://github.com/marbleprotocol)) - "Flash lending" protocol for borrowing "Ether and ERC20 tokens to take advantage of arbitrage opportunities on Ethereum"


<a name="derivative-protocols" />

## Derivative Protocols / Prediction Markets

- Ethereum
  - [Augur](https://www.augur.net) ([source code](https://github.com/AugurProject/augur), [white paper](https://www.augur.net/whitepaper.pdf)) - Prediction market protocol to enable anyone to "create and speculate on derivatives at a low cost for the first time"
  - [bZx](https://b0x.network) ([source code](https://github.com/bZxNetwork), [white paper](https://b0x.network/pdfs/b0x_white_paper.pdf)) - 0x-integrated protocol for decentralized, peer-to-peer margin funding and trading
   - [CDx](https://cdxproject.com) ([white paper](https://cdxproject.com/assets/resources/cdx-whitepaper.pdf)) - Protocol for tokenized credit default swaps
  - [dYdX](http://dydx.exchange) ([source code](https://github.com/dydxprotocol/protocol), [white paper](https://whitepaper.dydx.exchange/)) - Margin-trading and options protocols
  - [Gnosis](http://gnosis.pm) ([source code](https://github.com/gnosis), [white paper](https://gnosis.pm/assets/pdf/gnosis-whitepaper.pdf)) - Decentralized prediction market protocol
  -  [Market](https://marketprotocol.io) ([source code](https://github.com/MARKETProtocol), [white paper](https://marketprotocol.io/assets/MARKET_Protocol-Whitepaper.pdf)) - Protocol for structuring peer-to-peer agreements that settle in the future based on the price of a reference asset

<a name="bundling-protocols" />



<a name="fund-protocols" />

## Fund Protocols

- Ethereum
  - [Fund Protocol](https://www.coinalpha.com/projects) ([source code](https://github.com/CoinAlpha/fund-protocol)) - Protocol for fund administration on the Ethereum blockchain
  - [Melonport](https://melonport.com) ([source code](https://github.com/melonproject), [green paper](https://github.com/melonproject/paper/blob/master/melonprotocol.pdf)) - Protocol for digital asset management
  
<a name="tokenization-protocols" />

## Tokenization Protocols
- Ethereum
  - [Harbor/R-Token](https://harbor.com) ([source code](https://github.com/harborhq), [white paper](https://harbor.com/rtokenwhitepaper.pdf)) - Compliant protocol for standardizing crypto-securities issuance and trading
  - [Polymath/ST-20](https://polymath.network) ([source code](https://github.com/PolymathNetwork), [white paper](https://polymath.network/whitepaper.html)) - Platform for tokenizing securities
  - [Abacus](https://abacusprotocol.com) ([soure code](https://github.com/abacusprotocol), [white paper](https://polymath.network/whitepaper.html)) - Protocol for permissioned tokens

<a name="misc" />

## Misc
- Ethereum
  - [8x Protocol](https://8xprotocol.com) ([source code](https://github.com/8xprotocol), [white paper](https://rawcdn.githack.com/8xprotocol/whitepaper/master/latest.pdf)) - Protocol for decentralized subscription payment
  
<a name="community" />

## Community
* [DeFi Reddit](https://www.reddit.com/r/defi/)

<a name="contributions" />

## Contributions

Your contributions are always welcome!

If you want to contribute to this list (please do), send me a pull request or contact me [@edwin](https://twitter.com/edwin).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
