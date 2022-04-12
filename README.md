# awesome-solana

## 👩‍🎤 User

### Wallet
- [Phantom Wallet](https://phantom.app/) A non-custodial, chrome extension, Solana crypto wallet
- [SolFlare](https://solflare.com/) Non-custodial wallet for Solana

### Bridge
- `Allbridge`: backed by `APYSwap` API 2022-Q1 Foundation: https://allbridge.io/
- `Wormhole`: just release v2, (liquidity still not stable `BSC`↔︎`ETH`↔︎`SOL`): https://wormholebridge.com/#/transfer

### Stake
- `Marinade`: Liquid Stake+Ref `SOL` get `mSOL` APY 6.16% and farm `SOL-mSOL`: https://marinade.finance/
- `Lido`: `stSol` Liquid Stake (planned Ref) APY 5.89%: https://solana.lido.fi/

### Farms
- `Raydium` (DEX on `Serum`): https://raydium.io/
- `APYSwap`: Stake(`ABR` APR 522.37%): https://stake.apyswap.com/
- 🐳 `Orca`: Pools(`ABR-USDC` APR 218%): https://www.orca.so/pools
- `Saber`: cross-chain stablecoin exchange, low and unable to sort APY: https://saber.so/
- `Mercurial` : Stable `wbBUSD-wbUSDC-wbUSDT-USDC` APY 14.33% : https://mercurial.finance/pools/wbbusd-4pool
- `Jupiter` : takes zero fees : https://jup.ag/stats

### Farm creation
- `Atrix`: https://app.atrix.finance/#/create/farm

### Yield Aggregator
- 🌷 `Tulip` Aggregates yield farms from `Raydium` and `Saber` : https://tulip.garden/leverage
- `Sunny` Aggregator (Solana's composable DeFi yield aggregator), low apy bad ui:  https://app.sunny.ag/
- `Francium`: Solana Yield Farming Calculator : https://francium.io/app/calculator

### Fundraising Protocol
- `Solanium`: https://solanium.io/

### NFT
- https://www.metaplex.com/
- https://solanart.io/

### DAO
- `Tribeca`: https://tribeca.so/
  > Tribeca is a protocol for creating, managing, and interacting with decentralized autonomous organizations on Solana.

### Explorer
- `SolScan`: https://solscan.io/token/orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE
- `Solona Explorer`: https://explorer.solana.com/address/orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE

### Token List
- https://github.com/solana-labs/token-list
- https://shipcapital.substack.com/p/drop-005-solana-tokendao

- - -

## 🧑🏻‍💻 Developer

### Must Read
- TLDR: https://2501babe.github.io/posts/solana101.html
- How smart contracts work on Solana’s Proof of History based blockchain: https://medium.com/solana-labs/high-performance-memory-management-for-smart-contracts-aa9b3bc950fb
- Solana Doc: https://docs.solana.com/
- [Sealevel parallel runtime](https://medium.com/solana-labs/sealevel-parallel-processing-thousands-of-smart-contracts-d814b378192)
- Solana Program Library (SLP): https://spl.solana.com/
  > The Solana Program Library (SPL) is a collection of on-chain programs targeting the Sealevel parallel runtime.
- Solana Development Tutorial: Things you should know before structuring your code: https://solongwallet.medium.com/solana-development-tutorial-things-you-should-know-before-structuring-your-code-807f0e2ee43
- Solana Transactions in Depth: https://medium.com/@asmiller1989/solana-transactions-in-depth-1f7f7fe06ac2
- Solana internals
  - Part 1: what are the native on-chain programs and why do they matter?
    > https://blog.soteria.dev/solana-internals-part-1-what-are-the-native-on-chain-programs-and-why-do-they-matter-61c981483e86
  - Part 2: how is a Solana program deployed and upgraded
    > https://blog.soteria.dev/solana-internals-part-2-how-is-a-solana-deployed-and-upgraded-d0ae52601b99
  - Part 3: the transaction processing unit (TPU)
    > https://blog.soteria.dev/solana-internals-part-3-the-transaction-processing-unit-tpu-79887af07a04
  - Part 4: the bank — a key component
    > https://blog.soteria.dev/solana-internals-part-4-the-bank-a-key-component-1d47b94cd705

### Rust
- Ultimate Rust Crash Course: https://github.com/CleanCut/ultimate_rust_crash_course
- Let's Get Rusty: https://www.youtube.com/channel/UCSp-OaMpsO8K0KkOqyBl7_w

### Basic examples
- `Figment` Learn: https://learn.figment.io/
- [Hello World](https://github.com/solana-labs/example-helloworld)
- [Hello Chainlink Price Feeds on Solana](https://blog.chain.link/how-to-build-and-deploy-a-solana-smart-contract/)
- [Break Solana](https://github.com/solana-labs/break)
- [R/W JSON format on the Solana contract](https://github.com/jamesbachini/Solana-JSON)
- [Program examples written in Rust](https://github.com/solana-labs/solana-program-library/tree/master/examples/rust)
- [Interface for creating and managing SPL Tokens](https://www.spl-token-ui.com/#/)
- Build unique generative NFTs on Solana with Candy Machine v2 and Hashlips Engine: https://learn.figment.io/tutorials/generative-nfts-on-solana-with-candy-machine-v2-and-hashlips

### Wallet/dApp examples
- SPL Token Wallet (`Serum`): https://github.com/project-serum/spl-token-wallet
- Library to allow Solana dApps to use third-party wallets to sign transactions: https://github.com/project-serum/sol-wallet-adapter
- 🏗 Solana App Scaffold: https://github.com/solana-labs/dapp-scaffold
- Web3 Solana, Near: https://github.com/russellwmy/web3-rs

### Video examples
- Building SmartContracts With #Solana and #Rust: https://www.youtube.com/watch?v=gA7hFdq2h9Q
- Solana Programming: Connect to Wallet, Send Money, Query Transaction History: https://www.youtube.com/watch?v=wVPGJ_CZTAw
- Build Dapps with Solana and Arweave: https://www.youtube.com/watch?v=Jz5v_u75xk8
- How to Anchor: An introduction to the Anchor Framework: https://www.youtube.com/watch?v=FmdPAwsqJC4
- Avareum - Hello Rust and Anchor Framework (Thai Language): https://www.youtube.com/watch?v=DUnvIO2d-lc
- Writing Smart Contracts on Solana with Anchor by Armani Ferrante: https://youtu.be/cvW8EwGHw8U?t=10
- Why you should build your DeFi Dapp using Anchor by Henry Elder: https://youtu.be/725ddOvfWjk?t=23
- Programming Solana Smart Contracts | Hello World Anchor Tutorial by Henry Elder: https://youtu.be/oD1umX_DnUw
- Programming Solana Smart Contracts | Intermediate Anchor Tutorial by Henry Elder: https://youtu.be/i6Ycr5nhjH8
- PsyOptions Demo Video: https://youtu.be/wNM_MTQQSwY
- Foresight Demo Video - Prediction Markets: https://youtu.be/rL0bzGuwcdo
- Wormhole Video Tutorial - How use Wormhole: https://youtu.be/zooVxP5Ucws

### Advanced examples
- [Programming on Solana - An Introduction](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/): Building the escrow program
- [A Vesting Contract for the Solana Blockchain](https://github.com/Bonfida/token-vesting)
- [Token Vesting and Stream Payments](https://github.com/StreamFlow-Finance/timelock)
- [Staking](https://github.com/step-finance/step-staking) (Use `Anchor`)
- [Permissioned Markets](https://github.com/project-serum/permissioned-markets-quickstart) (Use `Serum`)
- The Complete Guide to Full Stack Solana Development with React, Anchor, Rust, and Phantom: https://dev.to/dabit3/the-complete-guide-to-full-stack-solana-development-with-react-anchor-rust-and-phantom-3291
- Swap: https://github.com/REGO350/macroswap
- Anchor: A Powerful Framework for Solana Developers: https://hackmd.io/@ironaddicteddog/solana-anchor-escrow
- Create a Solana dApp from scratch: https://lorisleiva.com/create-a-solana-dapp-from-scratch
  > Implement a simplified version of Twitter as a Solana dApp (decentralised application). We'll write our own program and use it in a custom VueJS app.

### Other examples
- Anchor (IDO, CFO, Swap, Multisig, Escrow, Game, Chat, Proxy, ...): https://github.com/project-serum/anchor/tree/master/tests
- Voting App: https://medium.com/@smith_10562/a-simple-solana-dapp-tutorial-6dedbdf65444
- The Rust-only Voting example based on MoonZoon and Solana: https://github.com/MartinKavik/voting-solana-moonzoon
- Solana File Upload: https://github.com/mcf-rocks/solana-upload
- SPL Token UI: https://github.com/paul-schaaf/spl-token-ui
- SPL Token Faucet: https://github.com/paul-schaaf/spl-token-faucet
  > Token faucets allow developers to easily give others access to tokens of a specific mint without sending around their private key. This is accomplished through a token faucet program.
  >
  > When creating a token faucet, the chosen token's mint authority is transferred to a Program Derived Address. The program then accepts minting requests. Having received such a request, the program checks that the requested amount is lower than the configured max amount or that the requester is the faucet admin (in which case they may mint as much as they like). These parameters can be set during faucet creation. Finally, a faucet may be closed again but only if it has an admin configured which must sign the closure tx. Faucet closure will transfer the token's mint authority back to the admin.
- Messaging App (POC): https://github.com/kemargrant/soltalk

### Libraries & Frameworks
- Solana Program Library (SPL) is a collection of on-chain programs targeting the Sealevel parallel runtime: https://github.com/solana-labs/solana-program-library/blob/master/examples/rust/README.md
- [Anchor Framework](https://project-serum.github.io/anchor/getting-started/introduction.html): a framework for Solana's Sealevel runtime providing several convenient developer tools : https://project-serum.github.io/anchor/tutorials/tutorial-0.html
- [StreamingFast Solana library for Go](https://github.com/streamingfast/solana-go)
- [Rust Library for the Binance API](https://github.com/wisespace-io/binance-rs)

### Farm SDK
- Orca: https://github.com/orca-so/typescript-sdk
- Francium: https://github.com/Francium-DeFi/francium-sdk

### Full Stacks
- Tokio: https://tokio.rs/
  > Tokio is an asynchronous runtime for the Rust programming language. It provides the building blocks needed for writing network applications. It gives the flexibility to target a wide range of systems, from large servers with dozens of cores to small embedded devices.

### `RPC` servers
- Project Serum: https://solana-api.projectserum.com (**recommended**)
- Figment-Solana: https://docs.figment.io/network-documentation/solana/rpc-and-rest-api
- Solana: https://api.mainnet-beta.solana.com (**can be unstable**)
- GenesysGo: https://genesysgo.com/
- RunNode: https://runnode.com/
- Triton RPC Pool: https://rpcpool.com/
- Blockdaemon: https://blockdaemon.com/marketplace/solana/
- Syndica: https://syndica.io/
- QuickNode: https://quicknode.com/

### Data/API
- Token list: https://github.com/solana-labs/token-list/blob/main/src/tokens/solana.tokenlist.json
- `Serum` Price API by `Sonar`: https://docs-price-api.sonar.watch/
- DataHub: https://figment.io/datahub/
- Flux Protocol (cross-chain oracle aggregator): https://www.fluxprotocol.org/
- [Serum Vial](https://github.com/tardis-dev/serum-vial) - real-time WebSocket market data API for Serum
- Bonfida: https://docs.bonfida.com/#exchanges
- Bitquery: https://graphql.bitquery.io/ - graphql for Solana blockchain, [article](https://bitquery.io/blog/solana-api)

### Oracle
- Pyth provides real-time on-chain market data: https://pyth.network/
- Switchboard allows builders to create data feeds from any API: https://switchboard.xyz/

### Price examples
- `curl 'https://price-api.sonar.watch/prices/orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE'`
- `curl 'https://api.solscan.io/account?address=orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE'`
- `Anchor` + `Pyth`: https://github.com/project-serum/anchor/blob/master/tests/pyth/tests/pyth.spec.ts

### Messaging
- `Wormhole` is a protocol for communication between different blockchains: https://wormholenetwork.com/

### Storage
- `Arweave` and Solana [partnered](https://medium.com/solana-labs/announcing-the-solar-bridge-c90718a49fa2) to provide a decentralised permanent data storage solution of ledger data: https://www.arweave.org/
- arweave-parallel-uploader: https://github.com/scottym5797/arweave-parallel-uploader
- `Ceramic` (Streaming `IPFS`): https://ceramic.network/

### Tools
- [SPL Token UI](https://spl-token-ui.com) for general token management on all clusters
- [Sollet.io](https://sollet.io) allows you to request airdops and mint test tokens where allowed
- [SPL Token Creator UI](https://www.spl-token-ui.com/)
- [Bonfida Token Minter](https://bonfida.com/mint)
- [SPL Manager](http://splmanager.com/)
- [honggfuzz-rs](https://github.com/rust-fuzz/honggfuzz-rs): Fuzz your Rust code with Google-developed Honggfuzz!
- https://github.com/lithdew/alon : Alon is an IDE which allows for developers to rapidly build, iterate, test, and deploy decentralized apps and assets on Solana right from their browser
- https://github.com/agoraxyz/agora-solana/blob/main/agsol-borsh-schema/README.md
  > A parsing library that generates TypeScript classes and serialization schemas from Rust data structures.

### Network status

- [@solanastatus](https://twitter.com/solanastatus) Twitter
- [Services status](https://status.solana.com/) an official site
- [Solana Beach](https://solanabeach.io/) services status and block explorer
- [Solana Validators](https://www.validators.app/) view validators statistics
- https://www.realtps.net/

### Ethereum related
- From Ethereum smart contracts to Solana programs: two common security pitfalls and beyond: https://medium.com/coinmonks/from-ethereum-smart-contracts-to-solana-programs-two-common-security-pitfalls-and-beyond-ea5b919ade1c
- [Neon EVM](https://neon-labs.org/) is an Ethereum virtual machine on Solana that enables dApp developers to use Ethereum tooling to scale and get access to liquidity on Solana.

### Others
- https://github.com/skywinder/web3swift : web3swift is an iOS toolbelt for interaction with the Ethereum network.
- https://github.com/ajamaica/Solana.Swift : Pure swift for Solana protocol.

### M1 related
- How to make Solana Test Validator work with a Macbook with M1 chip: https://dev.to/codenjobs/how-to-make-solana-test-validator-work-with-a-macbook-with-m1-chip-5emd

### WASM related
- A technical overview of developing gold.xyz: https://mirror.xyz/goldxyz.eth/cP4BqSyI_xP04VgRSsAtdDyDkvDcfUG_ZFgWYILDhjQ?123
  > `memmap2`, `rpc` workaround

- - -

## 👩‍🚀 Product Examples

### `Metaplex`
> [Metaplex](https://metaplex.com/) is a strategic partner of `Solana` Labs
- Create a `Solana` `NFT` marketplace and mint `NFT`s using `Metaplex` on `Arweave`: https://learn.figment.io/tutorials/create-a-solana-nft-marketplace-with-metaplex
- `Metaplex` Docs : https://docs.metaplex.com/architecture/deep_dive/overview

### `Serum`
> (FTX DEX backend): https://projectserum.com/
- [DEX source code](https://github.com/project-serum/serum-dex)
- [Serum.JS](https://github.com/project-serum/serum-js), client-side javascript resources to connect to the DEX
- [Serum DEX UI](https://github.com/project-serum/serum-dex-ui), an implementation of a UI for the Serum DEX
- Testnet deployment of prototype DEX
  - [DEX Program](https://explorer.solana.com/address/9JipvuvjcirpYf8mzYQtozXeYtQLWY67LaZCiANSMNgs)
  - [DEX Market](https://explorer.solana.com/address/2tJ2LVReFCZF81Ej4MAQHEr1kRSmk6QQ5XSnzjC9KJNj)
- Mainnet examples:
  - [DEX Program](https://explorer.solana.com/address/4ckmDgGdxQoPDLUkDT3vHgSAkzA3QRdNq5ywwY4sUSJn)
  - [DEX Market](https://explorer.solana.com/address/8AcVjMG2LTbpkjNoyq8RwysokqZunkjy3d5JDzxC6BJa)
- Swap based on Serum DEX orderbook:
  - [Swap UI](https://github.com/project-serum/swap-ui)
  - [Swap code](https://github.com/project-serum/swap)

### `Ceramic`
- Playground: https://developers.ceramic.network/explore/sample-apps/

### Step.finance
> Step Finance is a portfolio visualisation platform which aggregates all LPs, tokens, farms and positions that a user may have associated with their wallet and displays it in an easy to use dashboard with various useful metrics and visualisations. Step aims to be the page which DeFi users have open all day with all the functions and information they need to make informed decisions.
- Github: https://github.com/orgs/step-finance/repositories

### Bonfida
> Bonfida is a an on-chain and off-chain tool suite that enables the creation of trading pools.
- Github: https://github.com/Bonfida

### IdentitySwap (forked token-swap)
> IdentitySwap is an Automatic Money Market (AMM) dApp that demonstrates the concept of Decentralised Identity on the Solana SPL Token-Swap program. A user can interact with a liquidity pool only if they are in possession of a valid identity account, certified by a trusted identity validator.
- Github: https://github.com/civicteam/identity-swap

### StreamFlow Finance
> A powerful primitive that serves as a building block for various payment-related solutions.
- Github: https://github.com/StreamFlow-Finance

### Agrora http://agora.xyz
> Agora Space connects Discord, Twitter and other social media platforms with the blockchain providing a range of tools to upgrade DAOs and Social Token communities.
- Github: https://github.com/agoraxyz

### Cronos: https://www.cronos.so/
> Cronos is a decentralized task scheduler for Solana. 
- Github: https://github.com/cronos-so/cronos
- - -

### 😱 Pitfalls
- Solana Smart Contracts: Common Pitfalls and How to Avoid Them: https://blog.neodyme.io/posts/solana_common_pitfalls
- 10 vulnerabilities to avoid when writing Solana programs: https://twitter.com/pencilflip/status/1483880018858201090

- - -

## 🕵🏻‍♂️ Audit
- `Soteria` (Recommend): http://soteria.dev/
- `Soteria` — A vulnerability scanner for Solana smart contracts: https://medium.com/coinmonks/soteria-a-vulnerability-scanner-for-solana-smart-contracts-cc202cf17c99
- How to audit Solana smart contracts
  - Part 1: a systematic approach: https://medium.com/coinmonks/how-to-audit-solana-smart-contracts-part-1-a-systematic-approach-56a434f6c9ed
  - Part 2: automated scanning: https://medium.com/coinmonks/how-to-audit-solana-smart-contracts-part-2-automated-scanning-ceb88830ae6d
  - Part 3: penetration testing: https://medium.com/coinmonks/how-to-audit-solana-smart-contracts-part-3-penetration-testing-a315b3bbb2d3
  - Part 4: the Anchor framework: https://medium.com/coinmonks/how-to-audit-solana-smart-contracts-part-4-the-anchor-framework-ef42d944f086
- `Bonfida` by  Kudelski: https://github.com/Bonfida/token-vesting/blob/master/audit/Bonfida_SecurityAssessment_Vesting_Final050521.pdf
- `Quantstamp`: https://solana.com/SolanaQuantstampStakePoolAudit.pdf
- `Neodyme`: https://solana.com/SolanaNeodymeStakePoolAudit.pdf
- `Kudelski`: https://solana.com/SolanaKudelskiStakePoolAudit.pdf
- `Solido`: https://github.com/ChorusOne/solido/tree/main/audit
- `Saber.stable-swap`: https://github.com/saber-hq/stable-swap/blob/master/audit/bramah-systems.pdf
- `Quarry`: https://github.com/QuarryProtocol/quarry/blob/master/audit/quantstamp.pdf

- - - 

## Incident
- 2020-09-14 - Reflections on Solana's Sept 14 outage: https://jumpcrypto.com/reflections-on-the-sept-14-solana-outage/
- 2022-02-03 - The Wormhole Hack: https://blog.soteria.dev/the-wormhole-hack-how-soteria-detects-the-vulnerability-automatically-eb0f433e8071

- - -

## 🎙 Talks and Podcasts
- [Breakpoint 2021: Serum: Powering DeFi 2.0 / Writing Smart Contracts on Solana with Anchor](https://youtu.be/cvW8EwGHw8U)
- [Breakpoint 2021: Why You Should Build Your DeFi Dapp Using Anchor](https://youtu.be/725ddOvfWjk)
- [Breakpoint 2021: From Elsewhere: Oracles and Data Feeds](https://youtu.be/JlaSH1j42UI)
- [Breakpoint 2021: NFT Mechanics](https://www.youtube.com/watch?v=4qplEacSMvI)
