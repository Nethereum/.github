# Nethereum

The .NET integration platform for Ethereum and EVM-compatible blockchains. From smart contract interaction to a complete in-process Ethereum node, blockchain indexer, explorer, account abstraction bundler, MUD framework, multi-platform wallets, Unity integration, and .NET Aspire orchestration — 130+ packages targeting netstandard 2.0 through .NET 10 and Unity.

## Nethereum Core

The main Nethereum solution and projects: **[github.com/Nethereum/Nethereum](https://github.com/Nethereum/Nethereum)**

```
dotnet add package Nethereum.Web3
```

### What You Can Build

| I want to... | Section |
|---|---|
| Query balances, send ETH, interact with contracts | [Core Foundation](https://docs.nethereum.com/docs/core-foundation/overview) |
| Delegate an EOA to a smart contract (EIP-7702) | [Core Foundation](https://docs.nethereum.com/docs/core-foundation/guide-eip7702) |
| Sign with HD wallets, Ledger/Trezor, AWS KMS, Azure Key Vault | [Signing & Key Management](https://docs.nethereum.com/docs/signing-and-key-management/overview) |
| Deploy contracts, generate C# services from ABI | [Smart Contracts](https://docs.nethereum.com/docs/smart-contracts/overview) |
| Work with ERC-20/721/1155 tokens (built-in typed services) | [Smart Contracts](https://docs.nethereum.com/docs/smart-contracts/guide-built-in-standards) |
| Simulate transactions and preview state changes before signing | [EVM Simulator](https://docs.nethereum.com/docs/evm-simulator/overview) |
| Debug EVM execution step-by-step (opcodes, stack, storage) | [EVM Simulator](https://docs.nethereum.com/docs/evm-simulator/guide-evm-debugging) |
| Run a local dev chain — no external node required | [DevChain](https://docs.nethereum.com/docs/devchain/overview) |
| Spin up a full dev environment with .NET Aspire | [DevChain](https://docs.nethereum.com/docs/devchain/overview) |
| Swap tokens on Uniswap (V2/V3/V4) | [DeFi](https://docs.nethereum.com/docs/defi/guide-uniswap-swap) |
| Accept or pay for crypto payments (x402) | [DeFi](https://docs.nethereum.com/docs/defi/guide-x402-payments) |
| Execute Gnosis Safe multi-sig transactions | [DeFi](https://docs.nethereum.com/docs/defi/guide-gnosis-safe) |
| Use smart accounts and paymasters (ERC-4337) | [Account Abstraction](https://docs.nethereum.com/docs/account-abstraction/overview) |
| Deploy ERC-7579 modular smart accounts | [Account Abstraction](https://docs.nethereum.com/docs/account-abstraction/guide-modular-accounts) |
| Run an ERC-4337 bundler | [Account Abstraction](https://docs.nethereum.com/docs/account-abstraction/guide-run-bundler) |
| Index blockchain data to PostgreSQL / SQL Server / SQLite | [Data & Indexing](https://docs.nethereum.com/docs/data-and-indexing/overview) |
| Build a blockchain explorer (ABI decoding, contract interaction) | [Data & Indexing](https://docs.nethereum.com/docs/data-and-indexing/guide-explorer) |
| Get token prices, ABI from Etherscan/Sourcify, RPC via Chainlist | [Data Services](https://docs.nethereum.com/docs/data-services/overview) |
| Read, write, and index MUD table records | [MUD](https://docs.nethereum.com/docs/mud-framework/overview) |
| Build a multi-platform wallet app (Blazor, MAUI, Avalonia) | [Wallet SDK](https://docs.nethereum.com/docs/wallet-sdk/overview) |
| Connect browser wallets in Blazor (EIP-6963, WalletConnect, SIWE) | [Blazor dApp](https://docs.nethereum.com/docs/blazor-dapp-integration/overview) |
| Build Unity games with Ethereum | [Unity](https://docs.nethereum.com/docs/unity/overview) |
| Verify balances without trusting RPC (light client) | [Consensus](https://docs.nethereum.com/docs/consensus-light-client/overview) |
| Launch a custom application chain with sequencer and sync | [AppChains](https://docs.nethereum.com/docs/application-chain/overview) |

> For the full list of 100+ use cases with packages, see **[What Do You Want to Do?](https://docs.nethereum.com/docs/what-do-you-want-to-do)** or the **[Component Catalog](https://docs.nethereum.com/docs/component-catalog)**.

### Key Packages

| Package | NuGet | Description |
|---|---|---|
| [Nethereum.Web3](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Web3) | [![NuGet](https://badge.fury.io/nu/nethereum.web3.svg)](https://badge.fury.io/nu/nethereum.web3) | High-level entry point: RPC, contracts, accounts, signing |
| [Nethereum.Contracts](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Contracts) | [![NuGet](https://badge.fury.io/nu/nethereum.contracts.svg)](https://badge.fury.io/nu/nethereum.contracts) | Smart contract interaction with typed services for ERC-20, ERC-721, ERC-1155, ENS, and more |
| [Nethereum.Signer](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Signer) | [![NuGet](https://badge.fury.io/nu/Nethereum.Signer.svg)](https://badge.fury.io/nu/Nethereum.Signer) | Transaction signing, EIP-155/1559/4844/7702, message signing |
| [Nethereum.HdWallet](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.HdWallet) | [![NuGet](https://badge.fury.io/nu/Nethereum.HdWallet.svg)](https://badge.fury.io/nu/Nethereum.HdWallet) | BIP32/BIP39/BIP44 hierarchical deterministic wallets |
| [Nethereum.EVM](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.EVM) | [![NuGet](https://badge.fury.io/nu/Nethereum.EVM.svg)](https://badge.fury.io/nu/Nethereum.EVM) | Full in-process EVM simulator with debugging and state tracing |
| [Nethereum.DevChain.Server](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.DevChain.Server) | [![NuGet](https://badge.fury.io/nu/Nethereum.DevChain.Server.svg)](https://badge.fury.io/nu/Nethereum.DevChain.Server) | In-process Ethereum dev chain — no external node required |
| [Nethereum.BlockchainProcessing](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.BlockchainProcessing) | [![NuGet](https://badge.fury.io/nu/Nethereum.BlockchainProcessing.svg)](https://badge.fury.io/nu/Nethereum.BlockchainProcessing) | Blockchain data indexing with reorg detection and token transfer processing |
| [Nethereum.Explorer](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Explorer) | [![NuGet](https://badge.fury.io/nu/Nethereum.Explorer.svg)](https://badge.fury.io/nu/Nethereum.Explorer) | Blazor Server blockchain explorer with ABI decoding and contract interaction |
| [Nethereum.AccountAbstraction](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.AccountAbstraction) | [![NuGet](https://badge.fury.io/nu/Nethereum.AccountAbstraction.svg)](https://badge.fury.io/nu/Nethereum.AccountAbstraction) | ERC-4337 account abstraction + ERC-7579 modular smart accounts |
| [Nethereum.Mud](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Mud) | [![NuGet](https://badge.fury.io/nu/Nethereum.Mud.svg)](https://badge.fury.io/nu/Nethereum.Mud) | MUD autonomous worlds: table queries, store indexing, normalisation |
| [Nethereum.Uniswap](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Uniswap) | [![NuGet](https://badge.fury.io/nu/Nethereum.Uniswap.svg)](https://badge.fury.io/nu/Nethereum.Uniswap) | Uniswap V2/V3/V4 + Permit2 |
| [Nethereum.X402](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.X402) | [![NuGet](https://badge.fury.io/nu/Nethereum.X402.svg)](https://badge.fury.io/nu/Nethereum.X402) | HTTP 402 crypto payments (client + server middleware) |
| [Nethereum.GnosisSafe](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.GnosisSafe) | [![NuGet](https://badge.fury.io/nu/Nethereum.GnosisSafe.svg)](https://badge.fury.io/nu/Nethereum.GnosisSafe) | Gnosis Safe multi-sig integration |
| [Nethereum.Siwe](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Siwe) | [![NuGet](https://badge.fury.io/nu/Nethereum.Siwe.svg)](https://badge.fury.io/nu/Nethereum.Siwe) | Sign-In with Ethereum (EIP-4361) |
| [Nethereum.Wallet](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Wallet) | [![NuGet](https://badge.fury.io/nu/Nethereum.Wallet.svg)](https://badge.fury.io/nu/Nethereum.Wallet) | Multi-platform wallet core: accounts, vault, transaction services |
| [Nethereum.Blazor](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.Blazor) | [![NuGet](https://badge.fury.io/nu/Nethereum.Blazor.svg)](https://badge.fury.io/nu/Nethereum.Blazor) | Blazor dApp integration: EIP-6963 wallet discovery, auth state |
| [Nethereum.AppChain.Sequencer](https://github.com/Nethereum/Nethereum/tree/master/src/Nethereum.AppChain.Sequencer) | [![NuGet](https://badge.fury.io/nu/Nethereum.AppChain.Sequencer.svg)](https://badge.fury.io/nu/Nethereum.AppChain.Sequencer) | Custom application chain with EVM, sequencer, and AppChainBuilder |

All packages: [nuget.org/profiles/nethereum](https://www.nuget.org/profiles/nethereum)

## Nethereum Playground

Try Nethereum directly in your browser — chain interaction, Ether transfers, ERC20/ERC721, ENS, SIWE, HD wallets, log processing, and more.

[![Nethereum Playground](https://raw.githubusercontent.com/Nethereum/Nethereum/master/screenshots/playground.png)](http://playground.nethereum.com)

## Templates

Get started quickly with `dotnet new` templates:

```
dotnet new install Nethereum.Templates.Pack
dotnet new install Nethereum.Aspire.TemplatePack
```

| Template | Short Name | Description |
|---|---|---|
| Smart Contract Library + ERC20 XUnit | `smartcontract` | Smart contract dev with auto code generation and integration tests |
| ERC721/ERC1155 Open Zeppelin | `nethereum-erc721-oz` | NFT and multi-token development with OpenZeppelin |
| Blazor MetaMask Wasm/Server | `nethereum-mm-blazor` | Blazor + MetaMask integration |
| Blazor SIWE Wasm/Server/REST | `nethereum-siwe` | Sign-In with Ethereum authentication |
| WebSocket Streaming | `nethereum-ws-stream` | Real-time blockchain data streaming |
| Aspire DevChain Environment | `nethereum-devchain` | Full dev environment: DevChain + PostgreSQL + Indexer + Explorer |

Sources: [SmartContractDefault](https://github.com/Nethereum/Nethereum.Templates.SmartContractDefault), [OZ-Erc721-Erc1155](https://github.com/Nethereum/Nethereum.Templates.SmartContracts.OZ-Erc721-Erc1155), [Metamask.Blazor](https://github.com/Nethereum/Nethereum.Templates.Metamask.Blazor), [SIWE](https://github.com/Nethereum/Nethereum.Templates.Siwe)

## Wallets & End-to-End Examples

### Blazor / MAUI Hybrid Explorer Wallet

A .NET Blazor Wasm SPA, Desktop (Windows/Mac), Android and iOS light blockchain explorer and wallet.

Source: [Nethereum-Explorer-Wallet-Template-Blazor](https://github.com/Nethereum/Nethereum-Explorer-Wallet-Template-Blazor) | Try it: [explorer.nethereum.com](https://explorer.nethereum.com)

### Desktop Wallet (Avalonia)

A reactive cross-platform desktop wallet using Nethereum, Avalonia, and ReactiveUI.

Source: [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop)

## Unity

| Resource | Description |
|---|---|
| [Nethereum.Unity](https://github.com/Nethereum/Nethereum.Unity) | Unity package — install via git URL |
| [Unity3dSampleTemplate](https://github.com/Nethereum/Unity3dSampleTemplate) | Getting started: BlockNumber, Ether transfer, ERC20, MetaMask, cross-platform |
| [Nethereum.Unity.Webgl](https://github.com/Nethereum/Nethereum.Unity.Webgl) | WebGL + MetaMask: deploy ERC721 NFTs from Unity |

## Documentation & Community

- **Documentation**: [docs.nethereum.com](https://docs.nethereum.com)
- **Playground**: [playground.nethereum.com](http://playground.nethereum.com)
- **Discord**: [Join the community](https://discord.gg/u3Ej2BReNn) — technical support, chat, and collaboration
