# Awesome Hedera [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Join the chat at https://hedera.com/discord](https://img.shields.io/discord/373889138199494658.svg)](https://hedera.com/discord)

A curated list of awesome Hedera resources, applications, projects, and more!

## **Table of Contents**

- [Official Websites](README.md#official-websites)
- [Communities](README.md#communities)
- [Documentation and Training](README.md#documentation-and-training)
- [Articles and Presentations](README.md#articles-and-presentations)
- [Open Source Developer Assets](README.md#open-source-developer-assets)
  - [GitHub](README.md#github)
  - [Software Development Kits (SDKs)](README.md#software-development-kits-sdks)
  - [Examples and Demos](README.md#examples-and-demos)
  - [References and Resources](README.md#references-and-resources)
  - [Accelerators](README.md#accelerators)
- [Infrastructure and Integrations](README.md#infrastructure-and-integrations)
  - [Wallets](README.md#wallets)
  - [Custodians](README.md#custodians)
  - [Mirror Node/RPC Providers](README.md#mirror-noderpc-providers)
  - [Oracles](README.md#oracles)
  - [On-Ramps](README.md#on-ramps)
  - [Bridges and Interoperability](README.md#bridges-and-interoperability)
  - [Analytics and Risk/Compliance/KYT (Know Your Transaction)](README.md#analytics-and-riskcompliancekyt-know-your-transaction)
- [Hedera Projects](README.md#hedera-projects)
  - [Real World and Digital Asset Tokenization](README.md#real-world-and-digital-asset-tokenization)
    - [DeFi](README.md#defi)
    - [Real World Assets](README.md#real-world-assets)
    - [Payments](README.md#payments)
    - [Sustainability](README.md#sustainability)
  - [Data Integrity and Artificial Intelligence](README.md#data-integrity-and-artificial-intelligence)
  - [Consumer Engagement and Loyalty](README.md#consumer-engagement-and-loyalty)
    - [Enterprise](README.md#enterprise)
    - [Creator and Community Empowerment](README.md#creator-and-community-empowerment)
    - [Entertainment](README.md#entertainment)
    - [Community Initiatives](README.md#community-initiatives)
- [Contributing](README.md#contributing)
- [License](README.md#license)

## **Official Websites**

- [Hedera](https://hedera.com/) \- the only public network authorized to implement the hashgraph algorithm.
- [Hashgraph](https://www.hashgraph.com) \- Hashgraph supports the ongoing growth and development of Hedera.
- [Swirlds](http://www.swirlds.com/) \- inventors of the hashgraph consensus algorithm, offering licenses to use it in permissioned environments.
- [Hiero](https://hiero.org/) \- a Linux Foundation Decentralized Trust project, is an open-source, vendor-neutral distributed ledger technology. Hiero is used to build the Hedera public ledger.

## **Communities**

- [Discord](https://hedera.com/discord)
- [Telegram](https://t.me/hashgraph)
- [X - Main Account](https://x.com/hedera)
- [X - Developers Account](https://x.com/hedera_devs)
- [X - Spanish Account](https://x.com/hedera_ES)
- [X - Hashgraph Account](https://x.com/hashgraph)
- [LinkedIn](https://www.linkedin.com/company/hedera-network/posts/?feedView=all)
- [Stackoverflow](https://stackoverflow.com/questions/tagged/hedera)

## **Documentation and Training**

- [Hedera Documentation](https://docs.hedera.com)
- [Hedera for Web2 Developers](https://docs.hedera.com/hedera/getting-started/web2-developers)
- [Hedera for EVM Developers](https://docs.hedera.com/hedera/getting-started/evm-developers)
- [Tutorials](https://docs.hedera.com/hedera/tutorials)
- [Online training and certification course.](https://hashgraphdev.com/)
- [SDKs and Development tooling](https://docs.hedera.com/hedera/sdks-and-apis/sdks#hedera-services-code-sdks)
- [Accelerators and Integrations](https://docs.hedera.com/hedera/open-source-solutions)

## **Articles and Presentations**

- [Hedera Blog Articles](https://hedera.com/blog)
- [Hedera Articles on Medium](https://medium.com/hedera)
- [Hedera Developer Newsletter](https://hedera.com/developer-newsletter)

## **Open Source Developer Assets**

This section features open source projects in the [Hedera](https://www.hedera.com/) ecosystem.

### **GitHub**

- [Hedera](https://github.com/hashgraph)
- [Hedera Developers](https://github.com/orgs/hedera-dev/repositories)
- [Hiero](https://github.com/hiero-ledger)

### **Software Development Kits (SDKs)**

- [Java SDK](https://github.com/hiero-ledger/hiero-sdk-java) \- the official Java SDK for interacting with Hedera.
- [JavaScript SDK](https://github.com/hiero-ledger/hiero-sdk-js) \- the official JavaScript SDK for interacting with Hedera.
- [Go SDK](https://github.com/hiero-ledger/hiero-sdk-go) \- the official Go SDK for interacting with Hedera.
- [Swift SDK](https://github.com/hiero-ledger/hiero-sdk-swift) \- the official Swift SDK for interacting with Hedera.
- [Rust SDK](https://github.com/hashgraph/hedera-sdk-rust) \- the official Rust SDK for interacting with Hedera.
- [C++ SDK](https://github.com/hiero-ledger/hiero-sdk-cpp) \- the official C++ SDK for interacting with Hedera.
- Python SDK \- Work in progress.
- [DiD SDK (JavaScript)](https://github.com/hashgraph/did-sdk-js) \- Javascript SDK for managing DID Documents & Verifiable Credentials.
- [DiD SDK (Java)](https://github.com/hashgraph/did-sdk-java) \- Java SDK for managing DID Documents & Verifiable Credentials.
- [DiD Method](https://github.com/hashgraph/did-method) \- This repository contains the Hedera DID method specification.
- [NFT SDK](https://github.com/hashgraph/hedera-nft-sdk) \- Hedera NFT Utilities SDK for JavaScript
- [Hashgraph Online Standards SDK](https://github.com/hashgraph-online/standards-sdk) \- The official Hashgraph Online Standards SDK provides the RegistryBrokerClient for Universal Agentic Registry. Enables AI agent discovery, registration, blockchain-based identity (ERC-8004, UAIDs), and autonomous commerce via x402 protocol.
- [SDK TCK](https://github.com/hiero-ledger/hiero-sdk-tck) \- A TCK (Technology Compatibility Kit) used to verify compliant implementations of a Hiero SDK.
- [Hedera Custodians Library](https://github.com/hashgraph/hedera-custodians-library) \- The hedera-custodians-library library is a Typescript utility designed to simplify custodial wallet management. It provides developers with tools to abstract complex aspects of custodial wallets, allowing them to focus on their application's core logic.

### **Examples and Demos**

- [Hedera Developer Playground](https://portal.hedera.com/playground) \- This browser-based tool enables developers to write, execute, and share code snippets and flows directly in their web browser, utilizing the Hedera testnet. No wrestling with local setups.
- [Code snippets](https://github.com/hedera-dev/hedera-code-snippets) \- Short, Self Contained, Correct Examples of code on Hedera.
- [Bridging with Layer Zero](https://github.com/hedera-dev/hedera-example-layer-zero-bridging-oapp)
- [Chainlink price feeds](https://github.com/hedera-dev/hedera-example-chainlink-price-feeds)
- [Vanilla JS Dapp Template](https://github.com/hedera-dev/hedera-vanilla-js-dapp-template) \- A decentralized application template in pure JavaScript, HTML, and CSS. It uses Vite as its build tool.
- [Create React App Hedera Dapp Template](https://github.com/hedera-dev/cra-hedera-dapp-template) \- Hedera DApp Starter Template using Create React App, Material UI and Typescript with Hedera native wallet support and MetaMask wallet support.
- [Risk Calculator for Hedera Tokens](https://github.com/hedera-dev/risk-calculator-for-hedera-tokens) \- Risk Calculator application serves as a tool to evaluate the risk associated with tokens on the Hedera network, specifically to assess the likelihood of a rug pull based on a token's properties. It calculates a risk score and levels by examining various risk factors like Admin Key, Supply Key, KYC Key, etc.
- [Airdrop Verifier](https://github.com/hedera-dev/airdrop-verifier) \- The Airdrop Verifier is a utility that simplifies the process of organizing airdrops for Hedera tokens. Users can input a Token ID and a list of account IDs to which they wish to airdrop tokens. The application generates a list of addresses either associated with the token or having available auto-association slots, ensuring efficient and targeted airdrops.
- [Rarity Inspector](https://github.com/hedera-dev/rarity-inspector) \- This project allows users to upload a .zip file through a dropzone to check how NFTs are presented (displayed in a gallery as cards that can be clicked to read detailed information about them) and their "rarity". The project presents charts showing these data and several other features. Additionally, sorting and filtering options are available to simplify data browsing.
- [Token Holders List Builder](https://github.com/hedera-dev/token-holders-list-builder) \- The Token Holders List Builder is a tool designed to efficiently generate lists of token holders who meet specific criteria, like holding a minimum number of NFTs from a particular collection. This can be especially useful for identifying key stakeholders or organizing targeted marketing campaigns within the NFT community. By automating what would otherwise be a complex data retrieval process, this tool simplifies analytics and community management for NFT projects.
- [Hedera DApp Integrated with WalletConnec](https://github.com/hedera-dev/multi-wallet-hedera-transfer-dapp)t \- Explore DApp development using the Mirror Node API and Hedera Token Service (HTS). Discover how to integrate HTS functionality into your DApp for seamless token management and transactions. This guide uses React, Material UI, Ethers, and TypeScript with the Create React App (CRA) Hedera DApp template integrated with walletconnect, streamlining your development process.
- [Hedera DApp CRA Template](https://github.com/hedera-dev/cra-hedera-dapp-template-js) \- Hedera DApp Starter Template using Create React App, Material UI and JavaScript with HashPack, Blade, and MetaMask wallet support.
- [Hedera Tokens demo](https://github.com/hedera-dev/hedera-tokens) \- Example smart contracts to manage tokens on Hedera.
- [Supra Demo on Hedera | Push](https://github.com/hedera-dev/hedera-example-supra-oracle-contract-push) \- This example shows how to use Supra Oracles real-world data feeds (Push model).
- [Supra Demo on Hedera | Pull](https://github.com/hedera-dev/hedera-example-supra-oracle-contract-pull) \- This example shows how to use Supra Oracles real-world data feeds (Pull model). It fetches and verifies price data from Supra's gRPC server and use it within a smart contract on the Hedera network.
- [Example Pyth Oracle Contract Pull](https://github.com/hedera-dev/hedera-example-pyth-oracle-contract-pull) \- This demo is a simple example of how to use Pyth prices in Hedera and is based on the tutorial here. Follow the instructions in the tutorial to build and deploy and use this demo.
- [How to Test a Solidity Event with Foundry](https://github.com/hedera-dev/test-an-event-with-foundry) \- Foundry supports the use of cheatcodes. Cheatcodes allow you to go beyond testing the outputs of your smart contracts. They allow developers to manipulate the state of the blockchain, test for reverts, and events. In this tutorial, we will focus on the cheatcode vm.expectEmit to test a solidity event.
- [How to Deploy and Verify a Hedera Smart Contract with Foundry](https://github.com/hedera-dev/foundry-deploy-and-verify-smart-contract) \- Discover how to deploy and automatically verify your Hedera smart contract. Learn how to verify a pre-existing contract and check a contract's verification status.
- [How to Setup Foundry and Write a Basic Unit Test](https://github.com/hedera-dev/setup-foundry-and-write-basic-unit-test) \- Using an existing Hedera node project with the JavaScript SDK, learn how to set up Foundry to be able to leverage Forge, their command-line tool, to run your smart contract tests written in Solidity.
- [Hardhat example project](https://github.com/hashgraph/hedera-hardhat-example-project) \- This Hedera Hardhat Example Project offers boilerplate code for testing and deploying smart contracts via Hardhat. It includes configuration for both community-hosted and local (Hedera Local Node) instances of the Hedera JSON RPC Relay.
- [Hedera Smart Contract Starter](https://github.com/hashgraph/hedera-smart-contract-starter) \- This project provides a hands-on demonstration of using upgradeable smart contracts with OpenZeppelin's upgrades plugins in Hardhat. Specifically, it is a smart contract starter project that illustrates the use of both Proxies and Beacon Proxies.
- [HCS Chat application](https://github.com/hashgraph/hedera-hcs-chat-js) \- An example web app which demonstrates how you can use decentralized pub-sub messaging on the Hedera Consensus Service.
- [Hedera Subgraph Example](https://github.com/hashgraph/hedera-subgraph-example) \- The Hedera Subgraph Example Project demonstrates how to create and deploy a subgraph to a local graph node using The Graph Protocol. Based on the Hedera Hardhat Example Project Repository.
- [Proof of Action microservice](https://github.com/hashgraph/hedera-proof-of-action-microservice) \- The Hedera Proof of Action (HPoA) microservice aims to make it easy for organizations to build a capability to record and subsequently prove the existence of business events using the Hedera Consensus Service.
- [HTS Demo](https://github.com/hashgraph/hedera-hts-demo) \- This demo is a user interface written in Javascript (Vue.JS) to illustrate the use of the Hedera Token Service.

### **References and Resources**

- [Hackathon EVM starter sheet](https://github.com/hedera-dev/hedera-cheatsheets/blob/master/hedera-hackathon-starter-cheat-sheet-v1.pdf)
- [JSON RPC Relay](https://github.com/hashgraph/hedera-json-rpc-relay%20) \- implementation of an Ethereum JSON RPC APIs for Hedera.
- [Hashio](https://www.hashgraph.com/hashio/) \- Hashio is a Hashgraph-hosted service based on the open-source Hedera JSON-RPC-Relay. It provides a JSON-RPC API interface on top of Hedera’s native API transactions, offering a familiar Ethereum-like API.
- [HashScan](https://github.com/hashgraph/hedera-mirror-node-explorer) \- Visual Explorer for the Hiero DLT.
  - [https://hashscan.io/mainnet/dashboard](https://hashscan.io/mainnet/dashboard)
- [Walletconnect](https://github.com/hashgraph/hedera-wallet-connect) \- This repository is a reference for wallets and dApps integrating the WalletConnect \<\> Hedera JSON-RPC reference.
- [Mirror Node](https://github.com/hashgraph/hedera-mirror-node) \- An open-source implementation of the Hedera mirror node for developers and infrastructure providers to deploy.
- [Block Node](https://github.com/hashgraph/hedera-block-node) \- Implementation of the Hedera Block Node, which is responsible for consuming the block streams, maintaining state and exposing additional targeted value adding APIs to the Hedera community.
- [Solo](https://github.com/hashgraph/solo) \- An opinionated CLI tool to deploy and manage standalone test networks.
- [Hedera Local Node](https://github.com/hashgraph/hedera-local-node) \- Run your own local Hedera network for development purposes.
- [Hedera Protobufs](https://github.com/hashgraph/hedera-protobufs) \- Authoritative source of Hedera protobufs which represent the core of the Hedera Services API and enables developers to build libraries and SDKs in a multitude of development languages.
  - [Google Protocol Buffers](https://github.com/hashgraph/pbj) code generator, parser, and Gradle module.
- [Sourcify](https://github.com/hashgraph/hedera-sourcify) \- Tools for verifying Hedera smart contracts using standard open source libraries.
- [Hedera CLI](https://github.com/hashgraph/hedera-cli) \- A simple, open source, command line interface for interacting with both the Hedera Mainnet and Testnet.
- [The Graph](https://github.com/hashgraph/hedera-the-graph) \- Tools for hosting a graph node for the Hedera community.
- [Hedera Fee Tool](https://github.com/hashgraph/hedera-fee-tool-js) \- Tool to calculate price of transactions on Hedera network.
- [GRPCWeb Proxy](https://github.com/hashgraph/hedera-grpcWeb-proxy) \- This project contains a utility generator to create configuration files for docker such that you can run an envoy proxy for web clients to interact with Hedera's native APIs.
- [Smart Contracts](https://github.com/hashgraph/hedera-smart-contracts-libs-lab) \- Reference library for Smart Contracts utilized by the Hedera network with supporting files and examples.
- [Hedera Ledger App](https://github.com/hashgraph/ledger-app-hedera) \- Hedera wallet application for Ledger Nano S
- [Hash Name Service](https://github.com/hashingsystems/HNS) \- Replace your Hedera ID with human-readable names. Register your name before someone else does\!

### **Accelerators**

- [Stablecoin Studio](https://docs.hedera.com/hedera/open-source-solutions/stablecoin-studio/core-concepts) \- Stablecoin Studio is a set of open-source smart contracts and SDK that makes it easy for web3 stablecoin platforms, institutional issuers, enterprises, and payment providers to build stablecoin applications on the Hedera network.
- [Guardian](https://github.com/hashgraph/guardian%20) \- The [Guardian](https://docs.hedera.com/guardian) is an innovative open-source platform that streamlines the creation, management, and verification of digital environmental assets.
- [NFT Studio](https://docs.hedera.com/hedera/open-source-solutions/nft-studio) \- NFT Studio is a free, open-source toolkit that makes it easier to create and manage NFTs on the Hedera network.
  - Metadata Validator \- Validates NFT metadata against
    - Airdrop List Verifier \- Verifies which accounts are eligible to receive a specified token through an airdrop.
    - Rarity Inspector \- Analyzes unique traits of NFTs within a collection to generate a rarity score and assess value.
    - Token Holders List Builder \- Compiles a list of account IDs based on token holdings, quantity, and duration of ownership for community management.
    - Token Balance Snapshot \- Captures and filters the distribution of tokens across holders by the token amount and holding period.
- DAO-as-a-service boilerplate \- The starting point for developers building a DAO as a service on Hedera.
  - [https://github.com/hashgraph/hedera-accelerator-defi-dex](https://github.com/hashgraph/hedera-accelerator-defi-dex)
    - [https://github.com/hashgraph/hedera-accelerator-defi-dex-ui](https://github.com/hashgraph/hedera-accelerator-defi-dex-ui)
- RWA
  - [Asset Tokenization Studio](https://github.com/hashgraph/asset-tokenization-studio) \- Asset Tokenization Studio is a set of open-source smart contracts and SDK that makes it easy for asset issuers to manage bonds and equities in a regulatory-compliant manner with additional on-chain visibility on the Hedera network.
- DeFi
  - [Smart contracts for EIP 3643 & EIP 4626 that can be used on Hedera's EVM](https://github.com/hashgraph/hedera-accelerator-defi-eip)

## **Infrastructure and Integrations**

### **Wallets**

- [HashPack](https://hedera.com/users/hashpack)
- [Blade Wallet](https://bladewallet.io/)
- [BankSocial](https://hedera.com/users/banksocial)
- [Guarda](https://guarda.com/)
- [Wallawallet](https://wallawallet.com/)
- [Abra](https://www.abra.com/)
- [Atomic Wallet](https://atomicwallet.io/)
- [Coinomi](https://www.coinomi.com/en/)
- [Kabila](https://www.kabila.app/wallet)
- [Venly](https://www.venly.io/)
- [D’CENT](https://www.dcentwallet.com/en): Hardware wallet for Hedera tokens
- [Citadel Wallet](https://www.citadelwallet.io/): Hardware wallet for Hedera tokens
- [Ledger](https://www.ledger.com/): Hardware wallet for Hedera tokens

### **Custodians**

- [BitGo](https://www.bitgo.uk/products/custody-wallets/)
- [Coinbase Prime](https://www.coinbase.com/en-gb/prime)
- [Copper Co.](https://copper.co/en)
- [Fireblocks](https://www.fireblocks.com/)
- [Hex Trust](https://hextrust.com/)
- [Ledger](https://www.ledger.com/)

### **Mirror Node/RPC Providers**

- [Arkhia](https://www.arkhia.io/)
- [HashIO](https://www.hashgraph.com/hashio/)
- [Hgraph](https://www.hgraph.com/)
- [Ledger Works](https://www.lworks.io/)
- [LinkPool](https://linkpool.com/)
- [QuickNode](https://www.quicknode.com/)
- [Validation Cloud](https://www.validationcloud.io/)

### **Oracles**

- [Chainlink](https://chain.link/)
- [Pyth Network](https://www.pyth.network/)
- [Supra](https://supra.com/)

### **On-Ramps**

- [Banxa](https://banxa.com/)
- [C14](https://www.c14.money/)
- [Metallicus](https://www.metallicus.com/)
- [MoonPay](https://www.moonpay.com/en-gb)
- [Transak](https://transak.com/)

### **Bridges and Interoperability**

- [Axelar](https://www.axelar.network/)
- [HashPort](https://hedera.com/users/hashport)
- [LayerZero](https://layerzero.network/)
- [Magic Link](https://magic.link/)
- [MetaMask Snap](https://snaps.metamask.io/snap/npm/hashgraph/hedera-wallet-snap/)
- [WalletConnect](https://walletconnect.network/)
- [XP Network](https://xp.network/)

### **Analytics and Risk/Compliance/KYT (Know Your Transaction)**

- [ChainAbuse](https://www.chainabuse.com/)
- [Elliptic](https://www.elliptic.co/)
- [Hashpoint Research](https://www.hashpoint.io/)
- [TRM Labs](https://www.trmlabs.com/)
- [Tuum Technologies](https://www.tuum.tech/)

## **Hedera Projects**

Featuring projects built on top of or integrated with the [Hedera](https://www.hedera.com/) network.

### **Real World and Digital Asset Tokenization**

#### **DeFi**

- [BankSocial](https://hedera.com/users/banksocial): Open banking platform providing credit unions and their members with access to web3 services and offerings
- [Bonzo Finance](https://hedera.com/users/bonzo-finance): Decentralized lending and borrowing platform
- [Copper](https://copper.co/en): HBAR staking, custody, and decentralized finance services
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/copper-integration-affirms-hedera-network-as-an-institutional-defi-leader)
- [HeadStarter](https://hedera.com/users/headstarter): Hedera ecosystem enabler and launchpad for early stage projects
- [HeliSwap](https://app.heliswap.io/): Decentralized exchange (AMM)
- [HLiquity](https://hliquity.org/): Decentralized lending and borrowing platform
- [HSUITE](https://hedera.com/users/hsuite): Decentralized exchange (AMM) and NFT platform
- [ICHI](https://ichi.org/): Automated liquidity management and provision for DEXs
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/ichi-partnerships-bolster-hederas-trading-ux-and-market-efficiency)
- [SaucerSwap](https://hedera.com/users/saucerswap): Decentralized exchange (AMM)
- [Sirio Finance](https://www.sirio.finance/): Decentralized lending and borrowing platform
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/sirio-finance-unveils-ai-driven-lending-borrowing-protocol-on-the-hedera-network)

#### **Real World Assets**

- [abrdn](https://hedera.com/users/abrdn): Tokenized interests and payouts in £multi-billion money market fund to enable near-instant payout settlement and reinvestment. Plans to further explore tokenization for other financial products to improve efficiencies and reduce costs.
- [Archax](https://hedera.com/users/archax): Multi-chain institutional Tokenization-as-a-Service (TaaS) platform.
- [Diamond Standard](https://hedera.com/users/diamond-standard): Tokenized diamond platform bringing increased accessibility and liquidity to the diamond investment market.
- [OpenBrick](https://openbrick.co/): Real estate investment, financing, and tokenization platform.
- [RedSwan CRE](https://hedera.com/users/redswan): Regulated platform for tokenizing institutional-grade commercial real estate.
- [Scintilla](https://hedera.com/users/scintilla-by-dla-piper): Tokenization platform from DLA Piper for real world assets
- [Twigital](https://www.twigital.com/): Decentralized application for the tokenization of real world items
- [Zoniqx](https://hedera.com/users/zoniqx): Multi-chain institutional Tokenization-as-a-Service (TaaS) platform.

#### **Payments**

- [AUDD](https://www.audd.digital/): Australian Digital Dollar stablecoin built on Hedera.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/audd-to-launch-on-the-hedera-network)
- [Brale.xyz](https://brale.xyz/): Regulated stablecoin issuance and management stack with integrated on and offramps, treasury management, and reserves transparency.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/brale-integrates-the-hedera-network-for-regulated-stablecoin-issuance)
- [Dropp](https://hedera.com/users/dropp): Micropayment platform democratizing online transactions and enabling unlimited pricing flexibility.
- [EMTECH](https://hedera.com/users/emtech): Software-as-a-Service platform providing central banks and institutions with a comprehensive set of tools and services to digitally transform financial services.
- **Nomid**: Peer-to-peer payment solution leveraging Hedera to provide instant, low-cost, and secure transactions without intermediaries
- [PHPX](https://www.ledgerinsights.com/filipino-banks-plan-to-launch-multi-issuer-stablecoin-phpx-on-hedera-dlt/): Multi-bank Philippine peso stablecoin built on Hedera
- [StraitsX (XSGD)](https://www.straitsx.com/): Singapore dollar stablecoin built on Hedera
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/xsgd-the-southeast-asian-fiat-backed-stablecoin-from-straitsx-launches-on-hedera)
- [Universal Digital Payments Network (UDPN)](https://www.udpn.io/): Interoperable global payments network for regulated digital currencies such as stablecoins and CBDCs.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/udpn-integrates-stablecoins-and-cbdcs-issued-on-the-hedera-network)
- [USDC](https://hedera.com/users/usdc): Regulated USD stablecoin on the Hedera network
- [XeniPay](https://xenipay.com/): Instant, low-cost, transparent settlements for the travel industry

#### **Sustainability**

- [ALLCOT.IO](http://ALLCOT.IO): Powering environmental projects with cutting-edge technologies through ESG asset issuance and management
  - [HBAR Foundation blog](http://n)
- [BlockScience](https://block.science/): Enterprise analytics, engineering, and research solutions provider
- [B4ECarbon](http://chain-for-energy): Comprehensive carbon emissions management system combining blockchain, AI, and IoT technologies to provide end-to-end emissions tracking, reporting, and verification capabilities for the energy sector.
- [Capturiant](https://www.capturiant.com/): Global environmental asset authenticator, registry, and regulated exchange
- [CarbonBase](https://www.carbonbase.co/): Solutions provider empowering enterprises, individuals and communities to measure, reduce, and offset the carbon emissions
- [Demia](https://www.demia.net/): Scaling Carbon Markets through secure data logistics
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/welcoming-demia-to-the-hedera-ecosystem-a-milestone-in-advancing-trust-in-carbon-markets)
- [DOVU](https://hedera.com/users/dovu): Accelerating net zero by empowering the transparent digitization and trading of carbon at scale and at speed
- [Envision Blockchain](https://hedera.com/users/envision): Software-as-a-Service provider enabling organizations to recognize untapped value in Industry Vertical Solutions
- [Evercity](https://evercity.io/): ESG platform automating management, issuance and monitoring of sustainable finance
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/50-000-tonnes-of-digital-carbon-forwards-available-for-sale-on-evercity-platform)
- [HYPHEN](https://www.hyphen.earth): Swiss-based climate tech company driving improved digital measurement, reporting, and verification (dMRV) for carbon assets
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/hyphen-joins-the-hedera-guardian-ecosystem-to-elevate-the-integrity-of-carbon-credits-and-help-scale-the-carbon-markets-in-indonesia)
- [KrypC CarbonCore](https://hedera.com/users/krypcs-carboncore): Carbon market solution simplifying and streamlining carbon asset trading
- [NoviqTech](https://noviqtech.com/): Sustainability solutions provider for enterprises, institutions, and governments.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/tymlez-launches-on-hedera-with-hbar-foundation-support)
- [Tolam Earth](https://tolam.io/): Platform for organizations aiming to reach their sustainability and social development goals through the exchange of high-quality, high-impactful carbon assets.

### **Data Integrity and Artificial Intelligence**

- [Acoer](https://hedera.com/users/acoer): Healthcare solutions provider utilizing Hedera to address challenges in healthcare data management through tamper-proof logs, automated workflows, and transparent governance
- [MVC Global](https://hedera.com/users/avc-global): End-to-end supply chain management platform providing trusted data provenance for healthcare products
- [docStribute](https://hedera.com/users/docstribute): Immutable file sharing for regulated industries
- [EarthID](https://hedera.com/users/earth-id): Decentralized identity (DID) management platform
- [EQTY Lab](https://hedera.com/users/eqty-lab): AI integrity framework bringing accountability, usability, and transparency to artificial intelligence models
- [Everyware](https://hedera.com/users/everyware): Platform for connected healthcare systems to ensure safety standard and proper procedure through Hedera-secured data provenance
- [Fliggs Mobile](https://www.fliggsmobile.com/): Web3 mobile virtual network operator (MNVO) and decentralized identity provider
- [Fresh Supply Co.](https://fsco.io/): Supply chain digitalization platform bringing off-chain data on-chain.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/fresh-supply-co-fsco-payment-trigger-api-connects-hedera-to-mastercard-network)
- [Hala Systems](https://hedera.com/users/hala-systems): Advanced solutions provider for civilian and asset protection before, during, and after conflict.
- [HealthReady](https://www.gethealthready.com/): Transforming clinical trial study design and recruitment using a patient-driven approach to accelerate research and improve outcomes.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/healthready-optimises-healthcare-data-with-hedera-to-resolve-clinical-research-bottlenecks)
- [Supplier CO2 Emission Monitoring System (SCEMS)](https://www.hyundainews.com/en-us/releases/3895): Hedera-enabled carbon emissions tracking system providing data integrity and transparency for stakeholders at every stage of production.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/hyundai-motor-and-kia-introduce-co2-emission-monitoring-system-built-on-the-hedera-network)
- [KwikPik](https://kwikpik.io/): Delivery-as-a-Service (DaaS) platform for package delivery, tracking, and payment settlement.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/hedera-based-depin-kwik-pik-drives-financial-inclusion-throughout-africa-via-its-new-delivery-platform)
- [Meeco](https://hedera.com/users/meeco): Enterprise ESG solutions provider enabling deeper engagement with auditors and retail customers through data transparency.
- [Neuron](https://hedera.com/users/neuron): Decentralized service network connecting service providers directly with consumers in IoT systems, driving efficiency and cost-effectiveness.
- [OneSpan](https://www.onespan.com/): Cybersecurity company that provides digital identity verification, e-signatures, and fraud prevention solutions for financial institutions and enterprises.
- [Safe](https://hedera.com/users/safe-health-systems-inc): Digital healthcare platform for patient record management, population healthcare automation, and digital practice.
- [SEALCOIN](https://sealcoin.ai/): Platform enabling autonomous, real-time transactions between IoT devices
- [Taekion](https://taekion.com/): Decentralized cybersecurity and secure data storage solutions provider
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/taekion-leverages-hederas-public-consensus-for-safe-secure-on-chain-file-storage)
- [Tejouri](https://www.tejouri.com/): Decentralized ‘digital vault’ for important documents, multimedia, and files. Utilized by the DIFC Courts system in Dubai.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/difc-courts-launches-tijouri-the-global-digital-vault-built-on-hedera)
- [Theom](https://hedera.com/users/theom): Cloud data protection platform empowering enterprises to protect their data with transparency, real-time risk detection, and remediation guidance.
- [Things Protocol](https://hedera.com/users/things-protocol): Distributed IoT deceive management platform designed to secure device identity and provide value exchange between sensors and the outside world.

### **Consumer Engagement and Loyalty**

#### **Enterprise**

- [ServiceNow Now Platform](https://hedera.com/users/servicenow): Digital workflows secured and logged on Hedera for increased productivity, efficiency, and trust.
- [Unthink.ai](https://hedera.com/users/unthink): Enabling brands and creators to create context-oriented consumer interactions for deeper consumer engagement and brand loyalty.
- [Xeni](https://hedera.com/users/xeni): Travel platform enabling businesses to instantly create customized sales channels that deliver equitable and seamless travel experiences for all

#### **Creator and Community Empowerment**

- [Calaxy](https://hedera.com/users/calaxy): Web3-enabled social media platform with integrated NFT tools and cryptocurrency payments
- [GoMint](https://hedera.com/users/gomint): End-to-end tokenization solutions platform for enterprises, brands, developers, and more.
- [HashGuild](https://hashguild.xyz/): NFT marketplace
- [Kabila](https://hedera.com/users/kabila): Comprehensive Web3 platform empowering digital creators to own, monetize, and grow their communities with a comprehensive suite of tools to drive the creator economy.
- [LG Art Lab](https://hedera.com/users/lg): Sustainable NFT platform integrated with LG Electronics televisions featuring curated digital artwork
- [Liithos](https://liithos.com/): Entertainment studio championing the development of unique and engaging experiences for consumers
- [RoadCode](https://linktr.ee/roadcode): All-in-one pro cycling platform for professional riders/teams, loyal fans, fantasy league players, and amateur cyclists.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/the-worlds-best-pro-cycling-teams-ride-together-to-create-road-code-a-new-digital-fan-universe)
- [SentX](https://sentx.io/): NFT marketplace, launchpad, and analytics platform
- [Sphera World](https://www.spheraworld.com/): Sports entertainment engagement platform featuring collectibles and unique fan experiences
- [Thrive Hedera](https://thrivehedera.com/)**:** Empowering builders, creators, and DeFi enthusiasts creating value for the Hedera ecosystem.
- [TuneFM](https://hedera.com/users/tune-fm): Decentralized music streaming platform and marketplace

#### **Entertainment**

- [Dropper](https://dropper.vc/): Gaming launchpad and platform enabling early access to early stage projects on Hedera.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/droppers-gaming-launchpad-and-marketplace-launching-on-hedera-with-the-hbar-foundations-assistance)
- [Earthlings.land](https://www.earthlings.land/): Open-world metaverse fantasy game
- [Karate Combat](https://hedera.com/users/karate-combat): Combat sports entertainment league integrated with Hedera to transform consumer engagement and foster a more interactive, fan-centric experience with fighter benefits.
- [MetaverseME](https://www.metaverseme.com/): Metaverse avatar enablement platform empowering users and creators to express themselves in the digital world in unique ways.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/metaverseme-set-to-transform-web3-gaming-via-the-hedera-evm-partnering-with-thirdweb-and-the-hbar-foundation)
- [Reality+](https://realityplus.com/): Entertainment studio bridging the gap between Web2 and Web3 to create immersive, engaging new experiences.
  - [HBAR Foundation blog](https://www.hbarfoundation.org/blog-post/reality-chooses-hedera-to-mint-sell-and-trade-digital-collectibles-for-global-brands-and-ip)

#### **Community Initiatives**

- [The Barking Game (HBARK)](https://hbark.club/): Community game incentivizing engagement and content creation on social platforms.
- [The Mouth](https://www.wethemouth.com/): Web3-native marketing project experimenting with the intersection of digital assets and the attention economy.

## Contributing

We're always looking for awesome projects that showcase Hedera\! If you know of anything missing here, please [submit a pull request](https://github.com/hashgraph/awesome-hashgraph/pulls)\!  
When submitting, please try to maintain the existing structure and alphabetical order where possible. If you need to change the structure or other "meta" alterations, please [create a new issue](https://github.com/hashgraph/awesome-hashgraph).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
