# Awesome Web3 MCP Servers

A curated list of awesome Web3 Model Context Protocol (MCP) servers.

* [What is MCP?](#what-is-mcp)
* [Web3 MCP Categories](#web3-mcp-categories)


## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that standardizes how applications provide context to LLMs. Think of MCP like a USB-C port for AI applications. Just as USB-C provides a standardized way to connect your devices to various peripherals and accessories, MCP provides a standardized way to connect AI models to different data sources and tools.

![](https://github.com/demcp/awesome-web3-mcp-servers/blob/main/IMG/image1.jpg)


## Tutorials

* [Get started with the MCP (Official Introduction)](https://modelcontextprotocol.io/introduction)
* [What's New?  (Official Updates)](https://modelcontextprotocol.io/development/updates)
* [Development plans for MCP (Official Roadmap)](https://modelcontextprotocol.io/development/roadmap)


## What is DeMCP?

DeMCP is the first decentralized MCP network and a core infrastructure between AI and Web3. It focuses on providing Agents with self-developed and open-source MCP services, offering MCP developers a deployment platform with commercial revenue sharing, and enabling one-stop access to mainstream large language models (LLMs). By supporting crypto payments (USDT, USDC), DeMCP allows global developers to participate easily. Combined with TEE and a blockchain registry, DeMCP redefines the security and reliability of MCP, accelerating the advancement of the Agent industry.

👏 Follow [𝕏(Twitter) Group](https://x.com/DeMCP_AI) | Join [Telegram Group](https://t.me/DeMCPOfficial) | Visit [Official Web Site](https://www.demcp.ai)

![](https://github.com/demcp/awesome-web3-mcp-servers/blob/main/IMG/image2.jpg)


## Community

* [DeMCP Official Telegram](https://t.me/DeMCPOfficial)


## Web3 MCP Categories

* 🔗 - [Chain-RPC](#chain-rpc)
* 💰 - [Trading](#trading)
* 🔄 - [DeFi](#defi)
* 📊 - [Market Data](#market-data)
* 🛠️ - [Tool](#tool)
* 💬 - [Social](#social)


### 🔗 <a name="chain-rpc"></a>Chain-RPC

Chain-RPC MCP modules interact with multiple blockchains by abstracting their RPC layers into unified callable interfaces.

- [base/base-mcp](https://github.com/base/base-mcp) - This MCP server extends any MCP client's capabilities by providing tools to do anything on Base.
- [TermiX-official/bsc-mcp](https://github.com/TermiX-official/bsc-mcp) - A plug-and-play MCP tool server to send BNB, transfer BEP-20 tokens, deploy tokens, and interact with smart contracts on the Binance Smart Chain (BSC) — built for Claude Desktop, AI agents, and developers.
- [goat-sdk/goat](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol) - It is implemented for both EVM (Base Sepolia) and Solana chains but can be updated to support any other chain, wallet and series of tools.
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) - A comprehensive Model Context Protocol (MCP) server that provides blockchain services across multiple EVM-compatible networks.
- [strangelove-ventures/web3-mcp](https://github.com/strangelove-ventures/web3-mcp) - This server provides simple RPC endpoints for common blockchain operations, allowing secure interactions with various blockchains through environment variables.
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) - MCP (Model Context Protocol) server for blockchain data interaction through the Bankless API.
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) - An Model Context Protocol (MCP) server that enables AI models to interact with Bitcoin and Lightning Network, allowing them to generate keys, validate addresses, decode transactions, query the blockchain, and more.
- [crazyrabbitLTC/mcp-etherscan-server](https://github.com/crazyrabbitLTC/mcp-etherscan-server) - An MCP (Model Context Protocol) server that provides Ethereum blockchain data tools via Etherscan's API.
- [0xKoda/eth-mcp](https://github.com/0xKoda/eth-mcp) - An Model Context Protocol (MCP) server for interacting with Ethereum blockchain.
- [AbdelStark/lightning-mcp](https://github.com/AbdelStark/lightning-mcp) - An Model Context Protocol (MCP) server that enables AI models to interact with Lightning Network, allowing them to pay invoices.
- [marctheshark3/ergo-mcp](https://github.com/marctheshark3/ergo-mcp) - An Model Context Protocol (MCP) server for interacting with the Ergo blockchain.
- [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp) - An MCP server that powers AI agents with indexed blockchain data from The Graph.
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) - Algorand Model Context Protocol (Server & Client).
- [dcSpark/mcp-server-helius](https://github.com/dcSpark/mcp-server-helius) - an Model Context Protocol (MCP) server that provides Claude with access to Solana blockchain data via the Helius API.
- [itsanishjain/alchemy-sdk-mcp](https://github.com/itsanishjain/alchemy-sdk-mcp) - This MCP plugin provides integration with the Alchemy SDK for blockchain and NFT operations.
- [Dablclub/polygon-mcp](https://github.com/Dablclub/polygon-mcp) - An Model Context Protocol (MCP) server that provides onchain tools for Claude AI, allowing it to interact with the Polygon PoS blockchain.
- [lmcmz/flow-mcp-server](https://github.com/lmcmz/flow-mcp-server) - An Model Context Protocol (MCP) server for interacting with the Flow blockchain.
- [nearai/near-mcp](https://github.com/nearai/near-mcp) - An MCP server for the NEAR blockchain.
- [qvkare/linea-mcp](https://github.com/qvkare/linea-mcp) - An Model Context Protocol (MCP) server that provides on-chain tools for AI applications to interact with the Linea blockchain.
- [Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp) - An MCP server that provides enriched blockchain data from Codex. This server can be used with any MCP-compatible client like Claude Desktop.
- [mcpdotdirect/starknet-mcp-server](https://github.com/mcpdotdirect/starknet-mcp-server) - A comprehensive Model Context Protocol (MCP) server for the Starknet blockchain. This server provides AI agents with the ability to interact with Starknet networks, query blockchain data, manage wallets, and interact with smart contracts.
- [RomThpt/mcp-xrpl](https://github.com/RomThpt/mcp-xrpl) - A comprehensive Model Context Protocol (MCP) server that provides blockchain services for the XRP Ledger ecosystem.
- [hawkli-1994/go-sui-mcp](https://github.com/hawkli-1994/go-sui-mcp) - A Go-based management control plane server for Sui blockchain, providing MCP (Management Control Plane) tools to interact with local Sui client commands. This project integrates with Cursor IDE for enhanced development experience.


### 💰 <a name="trading"></a>Trading

Trading MCP modules perform trading operations by integrating with both DEX and CEX platforms through unified interfaces.

- [TermiX-official/binance-mcp](https://github.com/TermiX-official/binance-mcp) - Binance MCP Server is a backend service designed to interact with the Binance API.
- [TP Wallet MCP](https://www.npmjs.com/package/wallet-mcp?activeTab=readme) - TP Wallet MCP is an npm package that provides a seamless integration between AI Clients and user's crypto wallets.
- [dcSpark/mcp-server-jupiter](https://github.com/dcSpark/mcp-server-jupiter) - This repository contains a Model Context Protocol (MCP) server that provides Claude with access to Jupiter's swap API.
- [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) - An MCP server implementation enabling free USDC transfers on Base with Coinbase CDP MPC Wallet integration.
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) - An MCP server for AI agents to automate token swaps on Uniswap DEX across multiple blockchains.
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) - An MCP server that integrates with the Freqtrade cryptocurrency trading bot.
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) - An MCP server for executing token swaps on the Solana blockchain using Jupiter's new Ultra API.
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) - An MCP server providing tools for AI agents to mint ERC-20 tokens, supporting 21 blockchains.
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) - The MCP server for interacting with Blockchain, Swaps, Strategic Planning and more.
- [mektigboy/server-hyperliquid](https://github.com/mektigboy/server-hyperliquid) - An MCP server implementation that integrates the Hyperliquid SDK.
- [getalby/nwc-mcp-server](https://github.com/getalby/nwc-mcp-server) - Connect a bitcoin lightning wallet to your LLM using Nostr Wallet Connect (NWC or NIP-47).
- [sammcj/bybit-mcp](https://github.com/sammcj/bybit-mcp) - An MCP server that provides read-only access to Bybit's cryptocurrency exchange API.
- [b-open-io/bsv-mcp](https://github.com/b-open-io/bsv-mcp) - A collection of Bitcoin SV (BSV) tools for the Model Context Protocol (MCP) framework. This library provides wallet, ordinals, and utility functions for BSV blockchain interaction.
- [doubledare704/aiowhitebit-mcp](https://github.com/doubledare704/aiowhitebit-mcp) - Message Control Protocol (MCP) server and client implementation for WhiteBit cryptocurrency exchange API. Built on top of aiowhitebit library and fastmcp.
- [fere-ai/mcp-server](https://github.com/fere-ai/mcp-server) - A Model Conntext Protocol (MCP) server for interacting with the 0xMONK Trading Agent API.
- [georgyturevich/kuru-mcp-server](https://github.com/georgyturevich/kuru-mcp-server) - This project implements a Model Context Protocol (MCP) server for accessing Kuru.io crypto exchange data, making it accessible to LLMs and AI assistants.
- [solangii/upbit-mcp-server](https://github.com/solangii/upbit-mcp-server) - A server implementation for Upbit Cryptocurrency Exchange OpenAPI using the Model Context Protocol (MCP). This project provides tools to interact with Upbit exchange services, such as retrieving market data (quotes, orderbooks, trade history, chart data), account information, creating and canceling orders, managing deposits/withdrawals, and performing technical analysis.
- [collinsezedike/jupiter-mcp](https://github.com/collinsezedike/jupiter-mcp) - a TypeScript/Node.js MCP server that facilitates instant token swaps and limit orders seamlessly on Solana using Jupiter. It provides utilities for managing Solana token metadata, token balance checks, token lists, and wallet-based operations using environment-based configuration.


### 🔄 <a name="defi"></a>DeFi

DeFi MCP modules interact with DeFi protocols by abstracting their interfaces into standardized callable modules.

- [demcp/demcp-meson-mcp](https://github.com/demcp/demcp-meson-mcp) - A Meson cross-chain transaction MCP (Model Context Protocol) server implemented with Deno and TypeScript, helping users transfer assets conveniently between different blockchains.
- [demcp/defillama-mcp](https://github.com/demcp/defillama-mcp) - DeFiLlama MCP is a powerful and flexible tool that provides a microservice-based API wrapper around the DeFi Llama ecosystem.
- [kukapay/bridge-rates-mcp](https://github.com/kukapay/bridge-rates-mcp) - Delivering real-time cross-chain bridge rates and optimal transfer routes to onchain AI agents.
- [kukapay/chainlink-feeds-mcp](https://github.com/kukapay/chainlink-feeds-mcp) -  Providing real-time access to Chainlink's decentralized on-chain price feeds.
- [kukapay/defi-yields-mcp](https://github.com/kukapay/defi-yields-mcp) - An MCP server for AI agents to explore DeFi yield opportunities.
- [kukapay/pancakeswap-poolspy-mcp](https://github.com/kukapay/pancakeswap-poolspy-mcp) - An MCP server that tracks newly created liquidity pools on Pancake Swap, providing real-time data for DeFi analysts, traders, and developers.
- [kukapay/token-revoke-mcp](https://github.com/kukapay/token-revoke-mcp) - An MCP server for checking and revoking ERC-20 token allowances across multiple blockchains.
- [kukapay/uniswap-poolspy-mcp](https://github.com/kukapay/uniswap-poolspy-mcp) - An MCP server that tracks newly created liquidity pools on Uniswap across nine blockchain networks.
- [assetCLI/assetCLI-init](https://github.com/assetCLI/assetCLI-init) - assetCLI - Goldman Sachs for AI Agents. Winner of the Solana MCP AI Agent Competition. Vibe coding bonding curves, DEX & DAOs
- [collinsezedike/wormhole-mcp](https://github.com/collinsezedike/wormhole-mcp) - A TypeScript/Node.js Model Context Protocol (MCP) server that enables automatic transfer of tokens across multiple blockchains using the Wormhole SDK.


### 📊 <a name="market-data"></a>Market Data

Market Data MCP modules retrieve real-time market data from on-chain and off-chain sources via unified query interfaces.

- [Nayshins/mcp-server-ccxt](https://github.com/Nayshins/mcp-server-ccxt) - An Model Context Protocol (MCP) server that provides real-time and historical cryptocurrency market data through integration with major exchanges.
- [truss44/mcp-crypto-price](https://github.com/truss44/mcp-crypto-price) - A Model Context Protocol (MCP) server that provides comprehensive cryptocurrency analysis using the CoinCap API.
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) - An Model Context Protocol (MCP) server that connects to Heurist Mesh APIs, providing Claude with access to various blockchain and web3 tools.
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) - A coincap mcp server to access crypto data from coincap API.
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) - An MCP server that bridges Dune Analytics data to AI agents.
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) - Fetches real-time cryptocurrency prices, market cap, and volume data from CoinMarketCap.
- [badger3000/okx-mcp-server](https://github.com/badger3000/okx-mcp-server) - This project creates a Model Context Protocol (MCP) server that fetches real-time cryptocurrency data from the OKX exchange.
- [crazyrabbitLTC/mcp-coingecko-server](https://github.com/crazyrabbitLTC/mcp-coingecko-server) - An Model Context Protocol (MCP) server and OpenAI function calling service for interacting with the CoinGecko Pro API.
- [kukapay/blockbeats-mcp](https://github.com/kukapay/blockbeats-mcp) -  An MCP server that delivers blockchain news and in-depth articles from BlockBeats for AI agents.
- [kukapay/cointelegraph-mcp](https://github.com/kukapay/cointelegraph-mcp) -  Providing real-time access to the latest news from Cointelegraph.
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) - Provide the latest cryptocurrency news to AI agents, powered by CryptoPanic.
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) - An MCP server that provides real-time and historical Crypto Fear & Greed Index data, powered by the Alternative.me.
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) - An MCP server providing a range of cryptocurrency technical analysis indicators and strategie.
- [kukapay/crypto-news-mcp](https://github.com/kukapay/crypto-news-mcp) - An MCP server that provides real-time cryptocurrency news sourced from NewsData for AI agents.
- [kukapay/crypto-portfolio-mcp](https://github.com/kukapay/crypto-portfolio-mcp) - An MCP server for tracking and managing cryptocurrency portfolio allocations.
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) - An MCP server that delivers cryptocurrency sentiment analysis to AI agents.
- [kukapay/crypto-trending-mcp](https://github.com/kukapay/crypto-trending-mcp) - Tracking the latest trending tokens on CoinGecko.
- [kukapay/crypto-whitepapers-mcp](https://github.com/kukapay/crypto-whitepapers-mcp) - Serving as a structured knowledge base of crypto whitepapers.
- [kukapay/funding-rates-mcp](https://github.com/kukapay/funding-rates-mcp) - Providing real-time funding rate data across major crypto exchanges.
- [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp) - An MCP server that detects potential risks in Solana meme tokens.
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) - An Model Context Protocol (MCP) server for tracking cryptocurrency whale transactions using the Whale Alert API.
- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp/) - Deep Research for crypto - free & fully local.
- [openSVM/dexscreener-mcp-server](https://github.com/openSVM/dexscreener-mcp-server) - An MCP server implementation for accessing the DexScreener API, providing real-time access to DEX pair data, token information, and market statistics across multiple blockchains.
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) - Use Bitget’s API to get cryptocurrency info.
- [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) - A powerful and efficient Blockchain address risk scoring API MCP Server, leveraging the BICScan API to provide comprehensive risk assessments and asset information for blockchain addresses, domains, and decentralized applications (dApps).
- [CoinStatsHQ/coinstats-mcp](https://github.com/CoinStatsHQ/coinstats-mcp) - MCP Server for the CoinStats API. Provides access to cryptocurrency market data, portfolio tracking, and news.
- [tony-42069/solana-mcp](https://github.com/tony-42069/solana-mcp) - A comprehensive Solana MCP (Model Context Protocol) server for analyzing memecoins, tracking trends, and providing AI-powered insights using cultural analysis and on-chain data.
- [HubbleVision/hubble-ai-mcp](https://github.com/HubbleVision/hubble-ai-mcp) - Hubble is an AI-powered analytics tool that provides data analysis and visualization for Solana blockchain transactions with natural language queries.


### 🛠️ <a name="tool"></a>Tool

Tool MCP modules offer auxiliary utilities for Web3, supporting smart contract interactions, data processing, monitoring, and automation across decentralized systems.

- [solana-foundation/solana-dev-mcp](https://github.com/solana-foundation/solana-dev-mcp) - This repository demonstrates a simple implementation of a Model Context Protocol (MCP) server for Solana development.
- [CohumanSpace/digimon-engine](https://github.com/CohumanSpace/digimon-engine/tree/main/mcp) - Digimon Engine is an open-source gaming platform similar to Unreal Engine for AI gaming. It supports social and financial AI Agents, enabling immersive AI-native gameplay.
- [noditlabs/nodit-mcp-server](https://github.com/noditlabs/nodit-mcp-server) - A Model Context Protocol (MCP) server that connects AI agents and developers to structured, context-ready blockchain data across multiple networks through Nodit's Web3 infrastructure.


### 💬 <a name="social"></a>Social

Social MCP modules integrate with social platforms and protocols to enable identity management, messaging, and social graph interaction.

- [vidhupv/x-mcp](https://github.com/vidhupv/x-mcp) - An MCP server to create, manage and publish X/Twitter posts directly through Claude chat.
- [hanweg/mcp-discord](https://github.com/hanweg/mcp-discord) - An Model Context Protocol (MCP) server that provides Discord integration capabilities to MCP clients like Claude Desktop.
- [sparfenyuk/mcp-telegram](https://github.com/sparfenyuk/mcp-telegram) - The server is a bridge between the Telegram API and the AI assistants and is based on the Model Context Protocol.
- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) - Official Notion MCP Server.
- [kukapay/twitter-username-changes-mcp](https://github.com/kukapay/twitter-username-changes-mcp) - An MCP server that tracks the historical changes of Twitter usernames.

