# Awesome SVM

A curated list of projects and resources utilizing the Solana Virtual Machine (SVM).

## Projects

| Project Name     | Description                                                                                         | Status    | Links                                                                                         |
|------------------|-----------------------------------------------------------------------------------------------------|-----------|-----------------------------------------------------------------------------------------------|
| Eclipse          | Eclipse is building Solana on Ethereum, using the SVM to scale Ethereum.                             | Active    | [GitHub](https://github.com/Eclipse-Laboratories-Inc), [Website](https://www.eclipse.xyz/)      |
| Lollipop         | Proposes a formal specification for implementing SVM rollups on top of the Solana Layer 1 blockchain. | Development| [Whitepaper](https://arxiv.org/pdf/2405.08882.pdf), [Telegram](https://t.me/lollipopsvm)        |
| SOON             | Ethereum Layer 2 solution utilizing the Solana Virtual Machine to expedite transaction settlement.    | Development| [GitHub](https://github.com/soonlabs), [Telegram](https://t.me/soonlabs)                      |
| Termina          | Leverages the power of the Solana Virtual Machine to scale ecosystems with dedicated blockspace.      | Development| [Website](https://www.termina.technology/), [Telegram](https://t.me/terminatech)                |
| Nitro            | Optimistic rollup solution that enables Solana developers to port dApps to various ecosystems.       | Development| [Telegram](https://t.me/nitroprotocol), [Twitter](https://x.com/nitro_protocol)                 |
| Sonic SVM        | First chain extension on Solana, designed for games and applications, powered by the Sonic HyperGrid. | Development| [Website](https://www.sonic.game/)                                                             |
| MagicBlock       | Introduces Ephemeral Rollups, SVM-based runtimes enhancing performance for on-chain games.           | Development| [GitHub](https://github.com/magicblock-labs/ephemeral-rollups-spl), [Website](https://magicblock.gg/) |
| Fogo             | High-performance Layer 1 blockchain built on the Solana Virtual Machine for real-time experiences.    | Development| [Website](https://fogo.io), [Whitepaper](https://fogo.io/whitepaper)                           |
| Solayer          | Hardware-accelerated blockchain designed to infinitely scale the SVM for high-throughput applications. | Development| [Website](https://solayer.io), [Twitter](https://x.com/SolayerFdn)                             |
| Mantis           | Aims to revolutionize cross-chain trading and MEV extraction with multi-chain intent settlement.     | Development| [GitHub](https://github.com/ComposableFi/mantis-solana), [Website](https://mantis.app/)          |
| Code             | Mobile app leveraging self-custodial blockchain technology for a seamless payments experience.       | Development| [GitHub](https://github.com/code-payments/code-vm), [Website](https://getcode.com/)             |
| Grass            | Decentralized AI data collection network built on Solana, rewarding users for sharing bandwidth.     | Development| [Website](https://www.getgrass.io/), [Twitter](https://x.com/getgrass_io)                       |
| Atlas SVM        | Optimized for verifiable finance, combining traditional finance's performance with DeFi's transparency. | Development| [Website](https://www.atlas.xyz/)                                                             |
| Sovereign Labs   | Developing interoperable and scalable rollups leveraging proof aggregation and zk-rollup components. | Development| [GitHub](https://github.com/Sovereign-Labs), [Website](https://www.sovereign.xyz/)               |

# Solana Validator Implementations

A curated list of current Solana validator implementations, including both primary clients and notable modified versions used by validator operators.

## Validator Implementations

| Implementation | Website                     | X Handle                     | GitHub Repository                     | Team               |
|----------------|-----------------------------|------------------------------|---------------------------------------|--------------------|
| Agave          | [anza.xyz](https://anza.xyz) | [@anza_xyz](https://x.com/anza_xyz) | [anza-xyz/agave](https://github.com/anza-xyz/agave) | Anza core engineering team |
| Jito-Solana    | [jito.wtf](https://jito.wtf) | [@jito_labs](https://x.com/jito_labs) | [jito-foundation/jito-solana](https://github.com/jito-foundation/jito-solana) | Jito Labs |
| Sig            | [syndica.io/sig](https://syndica.io/sig) | [@Syndica_io](https://x.com/Syndica_io) | [Syndica/sig](https://github.com/Syndica/sig) | Syndica |
| Firedancer     | [docs.firedancer.io](https://docs.firedancer.io) | [@jump_firedancer](https://x.com/jump_firedancer) | [firedancer-io/firedancer](https://github.com/firedancer-io/firedancer) | Jump Crypto |
| Paladin        | [docs.paladin.one](https://docs.paladin.one) | [@paladin_solana](https://x.com/paladin_solana) | [paladin-bladesmith/paladin-solana](https://github.com/paladin-bladesmith/paladin-solana) | Paladin team <sup>[Modified from Jito-Solana]</sup> |

### Notes
- **Agave**: Primary client focused on reliability and network uptime, successor to the original Solana Labs validator.
- **Jito-Solana**: Adds MEV capabilities to enhance validator revenue and reduce network spam.
- **Sig**: Focuses on RPS optimization for improved user experience, written in Zig.
- **Firedancer**: High-performance client in C++, aimed at boosting throughput and resilience.
- **Paladin**: Modified version of Jito-Solana, enhancing MEV protection and block rewards for validators.



## Additional Resources

- **SVMKit:** A set of tools and libraries for developing on the Solana Virtual Machine
  - GitHub: [svmkit](https://github.com/solana-labs/svmkit)

- **Solana Vanity:** A tool for generating vanity addresses on Solana
  - GitHub: [solana-vanity](https://github.com/taiwanblockchainer/solana-vanity)

