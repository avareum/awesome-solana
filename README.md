# awesome-solana

## 👩‍🎤 User

### Wallet
- [Phantom Wallet](https://phantom.app/) A non-custodial, chrome extension, Solana crypto wallet
- [SolFlare](https://solflare.com/) Non-custodial wallet for Solana

### Bridge
- `Allbridge`: backed by `APYSwap` Foundation: https://allbridge.io/
- `Wormhole`: just release v2, (liquidity still not stable `BSC`↔︎`ETH`↔︎`SOL`): https://wormholebridge.com/#/transfer

### Farms
- `Raydium` (DEX on `Serum`): https://raydium.io/
- `APYSwap`: Stake(`ABR` APR 522.37%): https://stake.apyswap.com/
- 🐳 `Orca`: Pools(`ABR-USDC` APR 218%): https://www.orca.so/pools
- `Saber`: cross-chain stablecoin exchange, low and unable to sort APY: https://saber.so/

### Yield Aggregator
- 🌷 `Tulip` Aggregates yield farms from `Raydium` and `Saber` (`ORCA-USDC` APY 350.97%): https://tulip.garden/
- `Sunny` Aggregator (Solana's composable DeFi yield aggregator), low apy bad ui:  https://app.sunny.ag/

### Fundraising Protocol
- `Solanium`: https://solanium.io/

### NFT
- https://solanart.io/

### Explorer
- `SolScan`: https://solscan.io/token/orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE
- `Solona Explorer`: https://explorer.solana.com/address/orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE

- - -

## 🧑🏻‍💻 Developer

### Must Read
- Solana Doc: https://docs.solana.com/
- [Sealevel parallel runtime](https://medium.com/solana-labs/sealevel-parallel-processing-thousands-of-smart-contracts-d814b378192)
- Solana Program Library (SLP): https://spl.solana.com/
  > The Solana Program Library (SPL) is a collection of on-chain programs targeting the Sealevel parallel runtime.

### Good read
- Solana Transactions in Depth: https://medium.com/@asmiller1989/solana-transactions-in-depth-1f7f7fe06ac2

### Basic examples
- `Figment` Learn: https://learn.figment.io/
- [Hello World](https://github.com/solana-labs/example-helloworld)
- [Hello Chainlink Price Feeds on Solana](https://blog.chain.link/how-to-build-and-deploy-a-solana-smart-contract/)
- [Break Solana](https://github.com/solana-labs/break)
- [R/W JSON format on the Solana contract](https://github.com/jamesbachini/Solana-JSON)
- [Program examples written in Rust](https://github.com/solana-labs/solana-program-library/tree/master/examples/rust)
- [Interface for creating and managing SPL Tokens](https://www.spl-token-ui.com/#/)

### Wallet examples
- SPL Token Wallet (`Serum`): https://github.com/project-serum/spl-token-wallet
- Library to allow Solana dApps to use third-party wallets to sign transactions: https://github.com/project-serum/sol-wallet-adapter

### Video examples
- [Building SmartContracts With #Solana and #Rust](https://www.youtube.com/watch?v=gA7hFdq2h9Q)
- [Solana Programming: Connect to Wallet, Send Money, Query Transaction History](https://www.youtube.com/watch?v=wVPGJ_CZTAw)
- [Build Dapps with Solana and Arweave](https://www.youtube.com/watch?v=Jz5v_u75xk8)
- How to Anchor: An introduction to the Anchor Framework: https://www.youtube.com/watch?v=FmdPAwsqJC4

### Advanced examples
- [Programming on Solana - An Introduction](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/): Building the escrow program
- [A Vesting Contract for the Solana Blockchain](https://github.com/Bonfida/token-vesting)
- [Token Vesting and Stream Payments](https://github.com/StreamFlow-Finance/timelock)
- [Staking](https://github.com/step-finance/step-staking) (Use `Anchor`)
- [Permissioned Markets](https://github.com/project-serum/permissioned-markets-quickstart) (Use `Serum`)
- The Complete Guide to Full Stack Solana Development with React, Anchor, Rust, and Phantom: https://dev.to/dabit3/the-complete-guide-to-full-stack-solana-development-with-react-anchor-rust-and-phantom-3291
- Swap: https://github.com/REGO350/macroswap

### Other examples
- Anchor (IDO, CFO, Swap, Multisig, Escrow, Game, Chat, Proxy, ...): https://github.com/project-serum/anchor/tree/master/tests
- Voting App: https://medium.com/@smith_10562/a-simple-solana-dapp-tutorial-6dedbdf65444
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

### Data/API
- Token list: https://github.com/solana-labs/token-list/blob/main/src/tokens/solana.tokenlist.json
- `Serum` Price API by `Sonar`: https://docs-price-api.sonar.watch/
- DataHub: https://figment.io/datahub/
- Pyth provides real-time on-chain market data: https://pyth.network/
- Flux Protocol (cross-chain oracle aggregator): https://www.fluxprotocol.org/
- [Serum Vial](https://github.com/tardis-dev/serum-vial) - real-time WebSocket market data API for Serum
- Bonfida: https://docs.bonfida.com/#exchanges
- Bitquery: https://graphql.bitquery.io/ - graphql for Solana blockchain, [article](https://bitquery.io/blog/solana-api)

### Price examples
- `curl 'https://price-api.sonar.watch/prices/orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE'`
- `curl 'https://api.solscan.io/account?address=orcaEKTdK7LKz57vaAYr9QeNsVEPfiu6QeMU1kektZE'`

### Messaging
- `Wormhole` is a protocol for communication between different blockchains: https://wormholenetwork.com/

### Storage
- `Arweave` and Solana partnered to provide a decentralised permanent data storage solution of ledger data: https://www.arweave.org/
- `Ceramic` (Streaming `IPFS`): https://ceramic.network/

### Tools
- [SPL Token UI](https://spl-token-ui.com) for general token management on all clusters
- [Sollet.io](https://sollet.io) allows you to request airdops and mint test tokens where allowed
- [SPL Token Creator UI](https://www.spl-token-ui.com/)
- [Bonfida Token Minter](https://bonfida.com/mint)
- [SPL Manager](http://splmanager.com/)
- [honggfuzz-rs](https://github.com/rust-fuzz/honggfuzz-rs): Fuzz your Rust code with Google-developed Honggfuzz!
- https://github.com/lithdew/alon : Alon is an IDE which allows for developers to rapidly build, iterate, test, and deploy decentralized apps and assets on Solana right from their browser

### Network status

- [@solanastatus](https://twitter.com/solanastatus) Twitter
- [Services status](https://status.solana.com/) an official site
- [Solana Beach](https://solanabeach.io/) services status and block explorer
- [Solana Validators](https://www.validators.app/) view validators statistics

### Ethereum related
- [Neon EVM](https://neon-labs.org/) is an Ethereum virtual machine on Solana that enables dApp developers to use Ethereum tooling to scale and get access to liquidity on Solana.

### Others
- https://github.com/skywinder/web3swift : web3swift is an iOS toolbelt for interaction with the Ethereum network.
- https://github.com/ajamaica/Solana.Swift : Pure swift for Solana protocol.

### M1 related
- How to make Solana Test Validator work with a Macbook with M1 chip: https://dev.to/codenjobs/how-to-make-solana-test-validator-work-with-a-macbook-with-m1-chip-5emd

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

- - -

## 🕵🏻‍♂️ Audit
- `Bonfida` by  Kudelski: https://github.com/Bonfida/token-vesting/blob/master/audit/Bonfida_SecurityAssessment_Vesting_Final050521.pdf

- - -

## 🎙 Talks and Podcasts
- [Breakpoint 2021: Serum: Powering DeFi 2.0 / Writing Smart Contracts on Solana with Anchor](https://youtu.be/cvW8EwGHw8U)
- [Breakpoint 2021: Why You Should Build Your DeFi Dapp Using Anchor](https://youtu.be/725ddOvfWjk)
- [Breakpoint 2021: From Elsewhere: Oracles and Data Feeds](https://youtu.be/JlaSH1j42UI)
- [Breakpoint 2021: NFT Mechanics](https://www.youtube.com/watch?v=4qplEacSMvI)
