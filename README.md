# Awesome SVM

*Last Updated: May 22, 2025*

A curated list of projects and resources utilizing the Solana Virtual Machine (SVM).

## Machine-Readable Data

- [svm-networks.json](svm-networks.json) - JSON file containing structured data for all SVM networks and projects listed in this repository.

## Table of Contents

- [SVM Networks and Projects](#svm-networks-and-projects)
  - [Active Projects](#active-projects)
  - [Development Stage Projects](#development-stage-projects)
- [Solana Validator Implementations](#solana-validator-implementations)
  - [Validator Implementations](#validator-implementations)
  - [Validator Tools and Resources](#validator-tools-and-resources)
- [Development Tools and Libraries](#development-tools-and-libraries)
  - [Development Frameworks and SDKs](#development-frameworks-and-sdks)
  - [Client Libraries](#client-libraries)
  - [Development Tools](#development-tools)
  - [Infrastructure and APIs](#infrastructure-and-apis)
  - [Specialized Tools](#specialized-tools)
- [Research and Documentation](#research-and-documentation)
  - [Academic Papers](#academic-papers)
  - [Technical Articles and Whitepapers](#technical-articles-and-whitepapers)
  - [Technical Documentation](#technical-documentation)
  - [Industry Analysis](#industry-analysis)
- [Learning Resources](#learning-resources)
  - [Official Solana Foundation Resources](#official-solana-foundation-resources)
  - [Community Courses and Bootcamps](#community-courses-and-bootcamps)
  - [Tutorials and Guides](#tutorials-and-guides)
  - [Video Tutorials and Workshops](#video-tutorials-and-workshops)
  - [Documentation and Reference Materials](#documentation-and-reference-materials)
- [Community Resources](#community-resources)
  - [Forums and Discussion Platforms](#forums-and-discussion-platforms)
  - [Developer Communities](#developer-communities)
  - [Events and Conferences](#events-and-conferences)

## SVM Networks and Projects

### Active Projects

| Project Name | Description | Status | Links |
| --- | --- | --- | --- |
| Solana | The original Solana blockchain with the SVM | Active | [Website](https://solana.com), [Docs](https://docs.solana.com), [GitHub](https://github.com/solana-labs/solana), [Twitter](https://twitter.com/solana) |
| Eclipse | Eclipse is building Solana on Ethereum, using the SVM to scale Ethereum. | Active | [Website](https://www.eclipse.xyz/), [Docs](https://docs.eclipse.xyz/), [GitHub](https://github.com/eclipse-labs), [Twitter](https://twitter.com/EclipseFND) |
| Pythnet | Oracle network built on Solana, providing real-time price data | Active | [Website](https://pyth.network/), [GitHub](https://github.com/pyth-network), [Twitter](https://twitter.com/PythNetwork) |
| Hyperlane | Interoperable and scalable rollups leveraging proof aggregation and zk-rollup components | Active | [Website](https://www.hyperlane.xyz/), [GitHub](https://github.com/hyperlane-xyz), [Twitter](https://twitter.com/Hyperlane_xyz) |
| Bonk | Meme coin ecosystem built on Solana | Active | [Website](https://www.bonkcoin.com/), [Twitter](https://twitter.com/bonk_inu) |
| Airchains | Framework for creating customized rollups with support for EVM, SVM, and CosmWasm | Active | [GitHub](https://github.com/airchains-network) |
| SVM Wallet Maker | Python script to bulk-create wallets for Solana and other SVM-based blockchains | Active | [GitHub](https://github.com/svm-wallet-maker) |
| Chainlink Data Streams Solana | Repository for Data Streams Solana (SVM) Related Code | Active | [GitHub](https://github.com/smartcontractkit/chainlink-solana) |

### Development Stage Projects

| Project Name | Description | Status | Links |
| --- | --- | --- | --- |
| Lollipop | Proposes a formal specification for implementing SVM rollups on top of the Solana Layer 1 blockchain. | Development | [Whitepaper](https://arxiv.org/abs/2405.08882), [Telegram](https://t.me/lollipopchain) |
| SOON | Ethereum Layer 2 solution utilizing the Solana Virtual Machine to expedite transaction settlement. | Development | [GitHub](https://github.com/soonlabs), [Website](https://soon.network), [Telegram](https://t.me/soon_network) |
| Termina | Leverages the power of the Solana Virtual Machine to scale ecosystems with dedicated blockspace. | Development | [Website](https://termina.technology/), [Docs](https://docs.termina.network), [Twitter](https://twitter.com/TerminaTech), [Telegram](https://t.me/terminanetwork) |
| Nitro | Optimistic rollup solution that enables Solana developers to port dApps to various ecosystems. | Development | [Telegram](https://t.me/nitrochain), [Twitter](https://twitter.com/nitro_chain) |
| Sonic SVM | First chain extension on Solana, designed for games and applications, powered by the Sonic HyperGrid. | Development | [Website](https://www.sonic.game/), [Docs](https://docs.sonic.game), [Twitter](https://twitter.com/sonic_svm) |
| MagicBlock | Introduces Ephemeral Rollups, SVM-based runtimes enhancing performance for on-chain games. | Development | [GitHub](https://github.com/magicblock-labs), [Website](https://magicblock.gg) |
| Fogo | High-performance Layer 1 blockchain built on the Solana Virtual Machine for real-time experiences. | Development | [Website](https://fogo.network), [Whitepaper](https://docs.fogo.network) |
| Solayer | Hardware-accelerated blockchain designed to infinitely scale the SVM for high-throughput applications. | Development | [Website](https://solayer.org), [Twitter](https://twitter.com/solayerorg) |
| Mantis | Aims to revolutionize cross-chain trading and MEV extraction with multi-chain intent settlement. | Development | [GitHub](https://github.com/mantis-labs), [Website](https://mantis.network) |
| Code | Mobile app leveraging self-custodial blockchain technology for a seamless payments experience. | Development | [GitHub](https://github.com/code-wallet), [Website](https://getcode.com) |
| Grass | Decentralized AI data collection network built on Solana, rewarding users for sharing bandwidth. | Development | [Website](https://grass.network), [Twitter](https://twitter.com/grassnetwork) |
| Atlas SVM | Optimized for verifiable finance, combining traditional finance's performance with DeFi's transparency. | Development | [Website](https://atlas.xyz) |
| Sovereign Labs | Developing interoperable and scalable rollups leveraging proof aggregation and zk-rollup components. | Development | [GitHub](https://github.com/sovereign-labs), [Website](https://sovereign.xyz) |
| LessVM | SVM implementation project by openSVM | Development | [GitHub](https://github.com/openSVM/lessvm) |
| Mollusk | SVM program test harness for Solana development | Development | [GitHub](https://github.com/mollusk-svm) |
| Tilapia SVM | Freshwater Solana (SVM) rollup built for data and compute focused applications | Development | [GitHub](https://github.com/tilapia-svm) |
| HolySVM | HolyC program network extension for Solana | Development | [GitHub](https://github.com/holysvm) |
| Sig SVM | Proof-of-concept SVM implementation for Sig validator | Development | [GitHub](https://github.com/syndica/sig-svm) |
| EVM-SOL Wallet Abstraction | Wallet abstraction between Ethereum and Solana virtual machines | Development | [GitHub](https://github.com/evm-sol-wallet) |
| Solaxy | SVM-based Layer 2 solution | Development | N/A |
| Cube Chain | SVM-compatible blockchain | Development | N/A |
| JupNet | Jupiter-powered SVM network | Development | N/A |
| Polygon SVM | Polygon's SVM implementation | Development | N/A |
| Cascade | SVM-based scaling solution | Development | N/A |
| Yona Network | Bitcoin L2 using SVM technology | Development | N/A |
| SolanaVM | SVM implementation | Development | N/A |
| Light Protocol | Privacy-focused SVM solution | Development | N/A |
| Lulo | SVM-based network | Development | N/A |
| Sphere | SVM scaling solution | Development | N/A |
| Moonwalk | SVM implementation | Development | N/A |

## Solana Validator Implementations

A curated list of current Solana validator implementations, including both primary clients and notable modified versions used by validator operators.

### Validator Implementations

| Implementation | Website | X Handle | GitHub Repository | Team |
| --- | --- | --- | --- | --- |
| Agave | [anza.xyz](https://anza.xyz) | [@anza\_xyz](https://twitter.com/anza_xyz) | [anza-xyz/agave](https://github.com/anza-xyz/agave) | Anza core engineering team |
| Jito-Solana | [jito.wtf](https://jito.wtf) | [@jito\_labs](https://twitter.com/jito_labs) | [jito-foundation/jito-solana](https://github.com/jito-foundation/jito-solana) | Jito Labs |
| Sig | [syndica.io/sig](https://syndica.io/sig) | [@Syndica\_io](https://twitter.com/Syndica_io) | [Syndica/sig](https://github.com/Syndica/sig) | Syndica |
| Firedancer | [docs.firedancer.io](https://docs.firedancer.io) | [@jump\_firedancer](https://twitter.com/jump_firedancer) | [firedancer-io/firedancer](https://github.com/firedancer-io/firedancer) | Jump Crypto |
| Paladin | [docs.paladin.one](https://docs.paladin.one) | [@paladin\_solana](https://twitter.com/paladin_solana) | [paladin-bladesmith/paladin-solana](https://github.com/paladin-bladesmith/paladin-solana) | Paladin team \[Modified from Jito-Solana\] |

*   **Agave**: Primary client focused on reliability and network uptime, successor to the original Solana Labs validator.
*   **Jito-Solana**: Adds MEV capabilities to enhance validator revenue and reduce network spam.
*   **Sig**: Focuses on RPS optimization for improved user experience, written in Zig.
*   **Firedancer**: High-performance client in C++, aimed at boosting throughput and resilience.
*   **Paladin**: Modified version of Jito-Solana, enhancing MEV protection and block rewards for validators.

### Validator Tools and Resources

| Tool Name | Description | Status | Links | Metrics |
| --- | --- | --- | --- | --- |
| Solana Validator Manager | Tool for managing Solana validators | Active | [GitHub](https://github.com/mfactory-lab/sv-manager) | Last updated: Feb 2025, Actively maintained |
| Solana Identity Transition | Ansible Playbook for transitioning Solana Validator from primary to backup node | Active | [GitHub](https://github.com/rpcpool/solana-identity-transition) | Last updated: Feb 2025, Infrastructure tool |
| Solana Validator Lab | Deploy and test Agave validator features in a kubernetes-based cluster | Active | [GitHub](https://github.com/anza-xyz/svl) | Last updated: Jan 2025, Maintained by Anza team |
| Solana Hardware Compatibility List | HCL for running a Solana Mainnet Validator | Active | [GitHub](https://github.com/solana-foundation/solana-hcl) | Last updated: Mar 2025, Community-maintained resource |
| Solana Boot | Tooling and automation for Solana operators | Active | [GitHub](https://github.com/solana-labs/solana-boot) | Last updated: Feb 2025, Infrastructure automation |
| Sosh | Solana validator operations shell scripts | Active | [GitHub](https://github.com/dsrw/sosh) | Last updated: Feb 2025, Maintained by Solana core team member |
| Solana Cluster | Tooling to manage Solana snapshots | Active | [GitHub](https://github.com/blockdaemon/solana-cluster) | Last updated: Mar 2025, Maintained by Blockdaemon |
| Solana MEV | Decentralized MEV extraction from inside the validator | Active | [GitHub](https://github.com/ChorusOne/solana-mev) | Last updated: Mar 2025, Maintained by Chorus One |

## Development Tools and Libraries

### Development Frameworks and SDKs

| Tool | Description | Tags | Repository |
| --- | --- | --- | --- |
| Anchor | Solana program framework | Rust, TypeScript, Programs, dApps | [GitHub](https://github.com/coral-xyz/anchor) |
| AnchorPy | Anchor client library for Python | Python, dApps | [GitHub](https://github.com/kevinheavey/anchorpy) |
| Shank | IDL generation from Solana Native Rust | Rust, Programs | [GitHub](https://github.com/metaplex-foundation/shank) |
| Solita | Generates a TypeScript client for an IDL | TypeScript, Programs, dApps | [GitHub](https://github.com/metaplex-foundation/solita) |
| Seahorse | Python framework for writing Solana programs | Python, Programs | [GitHub](https://github.com/ameliatastic/seahorse-lang) |
| Nautilus | SQL-native Rust framework for Solana programs | Rust, TypeScript, Python, Programs | [GitHub](https://github.com/nautilus-project/nautilus) |
| Soda | Converts a JSON IDL to source code | Rust, TypeScript, Programs, dApps | [GitHub](https://github.com/Web3-Builders-Alliance/soda) |

### Client Libraries

| Tool | Description | Tags | Repository |
| --- | --- | --- | --- |
| Solana Wallet Adapter | Allows out-of-the-box components for providing web users a way to connect their wallet | TypeScript, dApps | [GitHub](https://github.com/solana-labs/wallet-adapter) |
| Solana Wallet Names | Resolves wallet names (.sol, glow, .abc, .backpack etc) to wallet addresses | TypeScript, dApps | [GitHub](https://github.com/portalpayments/solana-wallet-names) |
| Solana Unity SDK | Solana SDK for Unity game development | C#, C++, Unity, dApps, Games | [GitHub](https://github.com/magicblock-labs/Solana.Unity-SDK) |
| SolNet | Solana SDK for .NET framework | C#, .NET, dApps | [GitHub](https://github.com/bmresearch/Solnet) |
| Sol4k | Solana SDK for Kotlin | Kotlin, Java, dApps, Mobile | [GitHub](https://github.com/sol4k/sol4k) |
| Solathon | Python SDK for backend Solana applications | Python, dApps | [GitHub](https://github.com/SuperteamDAO/solathon) |
| EspressoCash | Flutter SDK for Solana | Flutter, dApps, Mobile | [GitHub](https://github.com/espresso-cash/espresso-cash-public) |
| Unreal Engine 5 SDK | Solana SDK for Unreal Engine 5 | C++, Unreal Engine, dApps, Games | [GitHub](https://github.com/raresloth/carbon) |
| Candy Pay | Seamless, mobile-native payment SDK | TypeScript, dApps, Mobile | [GitHub](https://github.com/candypay/elements) |
| Saganize | Kotlin mobile development suite | Kotlin, Java, dApps, Mobile | [GitHub](https://github.com/SAGAnize) |
| Gill | JavaScript/TypeScript client library for Solana blockchain | TypeScript, dApps | [GitHub](https://github.com/solana-labs/gill) |

### Development Tools

| Tool | Description | Tags | Repository |
| --- | --- | --- | --- |
| Amman | A set of tools to help test solana SDK libraries and apps on a locally running validator | TypeScript, Rust, Testing | [GitHub](https://github.com/metaplex-foundation/amman) |
| Solana NextJS Scaffold | Scaffold for getting up & running quickly with Solana & Next JS | TypeScript, dApps | [GitHub](https://github.com/solana-labs/dapp-scaffold) |
| `npx create-solana-dapp` | CLI command to deploy a configurable Solana scaffold repository | TypeScript, dApps | [GitHub](https://github.com/solana-developers/create-solana-dapp) |
| Oxylana Scaffold | Scaffold for quick-starting with Rust on Solana | Rust, Programs, dApps | [GitHub](https://github.com/cavemanloverboy/oxylana) |
| Xray | Human-readable Solana transaction explorer powered by Helius | Explorer, Programs, dApps | [GitHub](https://github.com/helius-labs/xray) |
| Better Call Sol | Open-source, web client for composing and submitting Solana transactions | Programs, dApps, GUI | [GitHub](https://github.com/labeleven-dev/bettercallsol) |
| Metaboss | The Metaplex NFT 'Swiss Army Knife' tool | Rust, CLI, NFTs | [GitHub](https://github.com/samuelvanderwaal/metaboss) |
| Nonci | API and SDK tool for queuing and executing transactions using durable nonces | Typescript, SDK, API | [GitHub](https://github.com/nonci-xyz) |
| SolSync | Enables on-chain applications to fetch and deserialize off-chain data | CLI, Programs, dApps | [GitHub](https://github.com/Web3-Builders-Alliance/SolSync) |
| Bokken | Debugger for Solana programs | Programs, Testing | [GitHub](https://github.com/Blade-Labs-Corp/bokken) |
| Arsnal | Debugging tools for Solana programs | Programs, Testing | [GitHub](https://github.com/AnishDe12020/arsnal) |
| SolStromm | CI/CD for Solana programs & dApps | YAML, Programs, dApps, CI/CD | [GitHub](https://github.com/Adithya2907/solana-devops/) |
| EventSnap | Leveraging on-chain events using an infrastructure-less approach | Rust, Programs, Logging | [GitHub](https://github.com/event-snap/event-snap) |
| anchor-errors | TUI explorer for errors of native programs and other popular Solana programs | Rust, Programs, Logging | [GitHub](https://github.com/acheroncrypto/anchor-errors) |
| Mucho | Command-line tool for development and testing of Solana blockchain programs | CLI, Programs | [GitHub](https://github.com/solana-labs/mucho) |

### Infrastructure and APIs

| Tool | Description | Tags | Repository/Website |
| --- | --- | --- | --- |
| Clockwork | Smart contract automation engine | Rust, Programs | [GitHub](https://github.com/clockwork-xyz/clockwork) |
| QuickNode | Fastest Solana RPC with global coverage and full archival data | RPCs, API, NFT API, Developer Tools | [Website](https://quicknode.com) |
| Chainstack | Suite of Web3 (including Solana) infrastructure services | Nodes, API, Data | [Website](https://chainstack.com/) |
| Helius Labs | Solana's leading RPCs, APIs, Webhooks, and Data Infrastructure | RPCs, API, Developer Tools, Compression | [GitHub](https://github.com/helius-labs) |
| Underdog API | Seamlessly integrate dynamic NFTs into your product | API, dApps | [Website](https://underdogprotocol.com/) |
| Concise Labs GraphQL API | GraphQL API for Solana program data | API, dApps | [Website](https://api-docs.conciselabs.io/docs/get-started/GraphQL%20API) |
| BlokHost | Decentralised Web Hosting & dCDN | dApps, Infrastructure | [GitHub](https://github.com/blokhost) |
| Tiny Dancer | Light client for Solana | dApps, Infrastructure | [GitHub](https://github.com/tinydancer-io) |
| Shadow Portal | Allows developers to summon off-chain data onto Solana | Rust, Programs | [GitHub](https://github.com/genesysgo/shadow-drive) |

### Specialized Tools

| Tool | Description | Tags | Repository |
| --- | --- | --- | --- |
| Stockpile | Community crowdfunding tools for a variety of projects and initiatives | Rust, Programs, dApps | [GitHub](https://github.com/StockpileProtocol/stockpile) |
| Elusiv SDK | SDK for adding zk-privacy to dApps | TypeScript, dApps, Privacy | [GitHub](https://github.com/elusiv-privacy/elusiv-sdk) |
| BastCtrl Tools | Web-based Token/NFT utility toolbox | GUI, Programs, dApps | [GitHub](https://github.com/BlastCtrl/blastctrl-tools) |
| SolDisperse | Web-based Token/NFT distributor | GUI, Programs, dApps | [GitHub](https://github.com/HotKeysInc) |
| Gamba | Create on-chain betting apps on Solana with zero deployments and no costs | TypeScript, dApps, Games | [GitHub](https://github.com/gamba-labs/gamba) |
| Carbon SDK | Bridges existing web2 game economies onto web3 | TypeScript, dApps, Games | [GitHub](https://github.com/raresloth/carbon) |
| Space Operator | Diagram what you want to build and press play | No-Code, Programs, dApps | [GitHub](https://github.com/space-operator) |
| SolCerberus | Role-based security layer for on-chain data access | Rust, TypeScript, Programs, dApps | [GitHub](https://github.com/solcerberus/solcerberus) |
| Solana Pay | A standard for decentralized payments on Solana | Payments, dApps | [GitHub](https://github.com/solana-labs/solana-pay) |

## Research and Documentation

### Academic Papers

| Title | Authors | Publication Date | Source | Description |
| --- | --- | --- | --- | --- |
| Lollipop: SVM Rollups on Solana | Irvin Steve Cardenas, Yugart Song | May 14, 2024 | [arXiv:2405.08882](https://arxiv.org/abs/2405.08882) | Formal specification for implementing Solana Virtual Machine (SVM) rollups on top of the Solana Layer 1 blockchain, including motivation, implementation details, design decisions, limitations, and preliminary results. |

### Technical Articles and Whitepapers

| Title | Author | Publication Date | Source | Description |
| --- | --- | --- | --- | --- |
| SVM Expansion: The Landscape Beyond Solana | Paul Timofeev | October 10, 2024 | [Hyperlane](https://medium.com/hyperlane/svm-expansion-the-landscape-beyond-solana-188757675fb6) | Comprehensive overview of SVM expansion beyond Solana, including SVM L2 implementations on Ethereum and Bitcoin, app-specific customizations, and extendable SVM environments. |
| What Is SVM - The Solana Virtual Machine | Squads Protocol | 2024 | [Squads Blog](https://squads.so/blog/solana-svm-sealevel-virtual-machine) | Detailed explanation of the Solana Virtual Machine, its architecture, Sealevel parallelization engine, and comparison with EVM. |
| What Is the Solana Virtual Machine (SVM)? | CoinGecko | May 28, 2024 | [CoinGecko](https://www.coingecko.com/learn/what-is-the-solana-virtual-machine-svm) | Overview of the SVM architecture, how it enables Solana to handle thousands of transactions per second, and its technical advantages. |
| What is SVM? — Solana Virtual Machine | MEXC Blog | July 21, 2024 | [MEXC Blog](https://blog.mexc.com/what-is-svm-solana-virtual-machine-creator-olaseni/) | Exploration of the Solana Virtual Machine, its mechanisms, and challenges towards scalability and adoption. |
| Opening up Solana (part 1) | Paul Arssov | August 14, 2024 | [Medium](https://paulars.medium.com/opening-up-solana-part-1-dc005b250c16) | Ideas on Solana Virtual Machine chains and the concept of 'opening' Solana by adding separate networks of nodes running Solana node software with SVM capabilities. |
| Solana: Past, Present, and Future | Nansen Research | October 4, 2023 | [Nansen Research Portal](https://research.nansen.ai/articles/solana-past-present-and-future) | Analysis of Solana's technological achievements, challenges, and future directions for infrastructure development, including SVM innovations. |

### Technical Documentation

| Title | Organization | Publication Date | Source | Description |
| --- | --- | --- | --- | --- |
| Execution - Solana Virtual Machine (SVM) | Eclipse | March 6, 2025 | [Eclipse Documentation](https://docs.eclipse.xyz/eclipse-architecture/what-is-eclipse-mainnet/execution-solana-virtual-machine-svm) | Technical documentation on how Eclipse Mainnet runs the Solana Virtual Machine (SVM) and integrates with existing SVM tooling. |
| Smart Contracts - EVM to SVM | Solana | 2024 | [Solana Developers](https://solana.com/developers/evm-to-svm/smart-contracts) | Guide for writing and deploying programs on the Solana blockchain, explaining the transition from EVM to SVM for developers. |
| Developing on the Solana Virtual Machine (SVM) | Eclipse | March 25, 2024 | [Eclipse Developer Guides](https://docs.eclipse.xyz/tutorials-and-guides/developer-guides/modifying-a-solana-dapp-to-support-eclipse-chomping-glass/developing-on-the-solana-virtual-machine-svm) | Guide on developing applications for the Solana Virtual Machine, including program structure and execution environment details. |

### Industry Analysis

| Title | Author | Publication Date | Source | Description |
| --- | --- | --- | --- | --- |
| Constructing Solana Virtual Machine (SVM) Ecosystems' Next Generation of Data Analytics | Sparsh | April 30, 2025 | [Medium](https://medium.com/@sparsh621/constructing-solana-virtual-machine-svm-ecosystems-next-generation-of-data-analytics-bde7571527fa) | Analysis of data analytics infrastructure for SVM ecosystems, highlighting projects like Helius, Solscan, and Solana FM that provide developer APIs for accessing on-chain data. |
| An article analyzing Solana virtual machine SOON | PANews | February 26, 2025 | [PANews](https://www.panewslab.com/en/articledetails/7u70e1h56k49.html) | Exploration of SOON's SVM technology and its applications in blockchain development. |
| SVM Track Overview: MoveVM Implementation | ChainCatcher | January 7, 2025 | [ChainCatcher](https://www.chaincatcher.com/en/article/2161319) | Overview of Eclipse as the first Layer 2 based on Solana Virtual Machine on Ethereum, combining Solana's speed with Ethereum's liquidity. |

## Learning Resources

### Official Solana Foundation Resources

| Resource | Provider | Type | Level | Link |
| --- | --- | --- | --- | --- |
| Solana Development Courses | Unboxed | Course Series | Beginner to Advanced | [Solana.com](https://solana.com/developers) |
| Solana Bootcamp | Solana Foundation | Comprehensive Course | Beginner to Intermediate | [Solana.com](https://solana.com/developers) |
| Solana Bytes | Solana Foundation | Short Tutorials | All Levels | [Solana.com](https://solana.com/developers) |
| Tutorials and Guides | Solana | Documentation | All Levels | [Solana.com/developers/guides](https://solana.com/developers/guides) |
| EVM to SVM: Complete Guide | Solana | Documentation | Intermediate | [Solana.com](https://solana.com/developers/evm-to-svm/complete-guide) |
| Smart Contracts - EVM to SVM | Solana | Documentation | Intermediate | [Solana.com](https://solana.com/developers/evm-to-svm/smart-contracts) |

### Community Courses and Bootcamps

| Resource | Provider | Type | Level | Link |
| --- | --- | --- | --- | --- |
| Build on Solana by Rise In | RiseIn.com | Course | Beginner to Intermediate | [RiseIn.com](https://risein.com) |
| Ethereum to Solana Developer Course | RareSkills.io | Course | Intermediate | [RareSkills.io](https://rareskills.io) |
| Solana Learning Track | Hackquest | Course | Beginner to Advanced | [Hackquest](https://hackquest.io) |
| Rust + Solana Advanced Development | CareerBooster.io | Course | Advanced | [CareerBooster.io](https://careerbooster.io) |
| Solana Developer Courses | Solayer | Course Series | All Levels | [Solayer Docs](https://docs.solayer.org/developers/learn-svm/guideline) |

### Tutorials and Guides

| Resource | Provider | Type | Focus | Link |
| --- | --- | --- | --- | --- |
| Developing on the Solana Virtual Machine (SVM) | Eclipse | Tutorial | SVM Development | [Eclipse Docs](https://docs.eclipse.xyz/tutorials-and-guides/developer-guides/modifying-a-solana-dapp-to-support-eclipse-chomping-glass/developing-on-the-solana-virtual-machine-svm) |
| CCIP Tutorials (SVM) | Chainlink | Tutorial Series | Cross-chain Development | [Chainlink Docs](https://docs.chain.link/ccip/tutorials/svm) |
| Prerequisites for SVM to EVM Tutorials | Chainlink | Guide | Cross-chain Setup | [Chainlink Docs](https://docs.chain.link/ccip/tutorials/svm) |
| Implementing CCIP Receivers | Chainlink | Tutorial | Cross-chain Communication | [Chainlink Docs](https://docs.chain.link/ccip/tutorials/svm) |
| SVM to EVM Guide | Chainlink | Guide | Cross-chain Development | [Chainlink Docs](https://docs.chain.link/ccip/tutorials/svm) |
| What is Solana's SVM? A Beginner's Guide | SDLC Corp | Guide | SVM Fundamentals | [SDLC Corp](https://sdlccorp.com/post/what-is-solanas-svm-a-beginners-guide-to-the-solana-virtual-machine/) |

### Video Tutorials and Workshops

| Resource | Provider | Type | Focus | Link |
| --- | --- | --- | --- | --- |
| Solana SVM Quick Walkthrough | YouTube | Video Tutorial | SVM Overview | [YouTube](https://www.youtube.com/watch?v=oqtdSIohwgs) |
| BP 2024: Workshop: SVM: The Power of Solana Beyond the Blockchain | Solana Compass | Workshop Recording | SVM Applications | [Solana Compass](https://solanacompass.com/learn/breakpoint-24/bp-2024-workshop-svm-the-power-of-solana-beyond-the-blockchain) |

### Documentation and Reference Materials

| Resource | Provider | Type | Focus | Link |
| --- | --- | --- | --- | --- |
| What Is the Solana Virtual Machine (SVM)? | Binance Academy | Article | SVM Fundamentals | [Binance Academy](https://academy.binance.com/en/articles/what-is-the-solana-virtual-machine-svm) |
| What Is the Solana Virtual Machine (SVM)? | CoinGecko | Article | SVM Architecture | [CoinGecko](https://www.coingecko.com/learn/what-is-the-solana-virtual-machine-svm) |
| What is SVM? — Solana Virtual Machine | MEXC Blog | Article | SVM Mechanisms | [MEXC Blog](https://blog.mexc.com/what-is-svm-solana-virtual-machine-creator-olaseni/) |

## Community Resources

### Forums and Discussion Platforms

- [Solana Stack Exchange](https://solana.stackexchange.com/) - Q&A site for Solana developers
- [Solana Forum](https://forums.solana.com/) - Official Solana community forum
- [Solana Subreddit](https://www.reddit.com/r/solana/) - Reddit community for Solana discussions

### Developer Communities

- [Solana Discord](https://discord.com/invite/solana) - Official Solana Discord server
- [Solana Developers Telegram](https://t.me/solana_developers) - Telegram group for Solana developers
- [Solana Collective](https://www.solanacollective.org/) - Community-driven Solana developer hub

### Events and Conferences

- [Solana Breakpoint](https://solana.com/breakpoint) - Annual Solana conference
- [Solana Hacker House](https://solana.com/hackhouse) - Global series of in-person hacking events
- [Solana Grizzlython](https://solana.com/grizzlython) - Solana's global hackathon series

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-contribution`)
3. Commit your changes (`git commit -m 'Add some amazing contribution'`)
4. Push to the branch (`git push origin feature/amazing-contribution`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all the contributors who have helped to expand this list
- Special thanks to the Solana Foundation and community for their support
- Resource count: 150+ SVM-related resources across all categories
