# Awesome Web3 MCP Servers

A curated list of awesome Web3 Model Context Protocol (MCP) servers.

* [What is MCP?](#what-is-mcp)
* [Web3 MCP Categories](#web3-mcp-categories)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that standardizes how applications provide context to LLMs. Think of MCP like a USB-C port for AI applications. Just as USB-C provides a standardized way to connect your devices to various peripherals and accessories, MCP provides a standardized way to connect AI models to different data sources and tools.

## Web3 MCP Categories

* 🔗 - [Chain-RPC](#chain-rpc)
* 💰 - [Trading](#trading)
* 🔄 - [DeFi](#defi)
* 📊 - [Market Data](#market-data)
* 💬 - [Social](#social)

### 🔗 <a name="chain-rpc"></a>Chain-RPC

Chain-RPC MCP modules interact with multiple blockchains by abstracting their RPC layers into unified callable interfaces.

- [base/base-mcp](https://github.com/base/base-mcp) - This MCP server extends any MCP client's capabilities by providing tools to do anything on Base.
- [TermiX-official/bsc-mcp](https://github.com/TermiX-official/bsc-mcp) - A plug-and-play MCP tool server to send BNB, transfer BEP-20 tokens, deploy tokens, and interact with smart contracts on the Binance Smart Chain (BSC) — built for Claude Desktop, AI agents, and developers.
- [goat-sdk/goat](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol) - It is implemented for both EVM (Base Sepolia) and Solana chains but can be updated to support any other chain, wallet and series of tools.
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) - A comprehensive Model Context Protocol (MCP) server that provides blockchain services across multiple EVM-compatible networks.
- [strangelove-ventures/web3-mcp](https://github.com/strangelove-ventures/web3-mcp) - This server provides simple RPC endpoints for common blockchain operations, allowing secure interactions with various blockchains through environment variables.
- [solana-foundation/solana-dev-mcp](https://github.com/solana-foundation/solana-dev-mcp) - This repository demonstrates a simple implementation of a Model Context Protocol (MCP) server for Solana development.
- [Bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp) - MCP (Model Context Protocol) server for blockchain data interaction through the Bankless API.
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) - An Model Context Protocol (MCP) server that enables AI models to interact with Bitcoin and Lightning Network, allowing them to generate keys, validate addresses, decode transactions, query the blockchain, and more.
- [crazyrabbitLTC/mcp-etherscan-server](https://github.com/crazyrabbitLTC/mcp-etherscan-server) - An MCP (Model Context Protocol) server that provides Ethereum blockchain data tools via Etherscan's API.
- [0xKoda/eth-mcp](https://github.com/0xKoda/eth-mcp) - An Model Context Protocol (MCP) server for interacting with Ethereum blockchain.
- [AbdelStark/lightning-mcp](https://github.com/AbdelStark/lightning-mcp) - An Model Context Protocol (MCP) server that enables AI models to interact with Lightning Network, allowing them to pay invoices.
- [marctheshark3/ergo-mcp](https://github.com/marctheshark3/ergo-mcp) - An Model Context Protocol (MCP) server for interacting with the Ergo blockchain.
- [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp) - An MCP server that powers AI agents with indexed blockchain data from The Graph.


### 💰 <a name="trading"></a>Trading

Trading MCP modules perform trading operations by integrating with both DEX and CEX platforms through unified interfaces.

- [dcSpark/mcp-server-jupiter](https://github.com/dcSpark/mcp-server-jupiter) - This repository contains a Model Context Protocol (MCP) server that provides Claude with access to Jupiter's swap API.
- [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) - An MCP server implementation enabling free USDC transfers on Base with Coinbase CDP MPC Wallet integration.
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) - An MCP server for AI agents to automate token swaps on Uniswap DEX across multiple blockchains.
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) - An MCP server providing tools for AI agents to mint ERC-20 tokens, supporting 21 blockchains.


### 🔄 <a name="defi"></a>DeFi

DeFi MCP modules interact with DeFi protocols by abstracting their interfaces into standardized callable modules.

- [kukapay/pancakeswap-poolspy-mcp](https://github.com/kukapay/pancakeswap-poolspy-mcp) - An MCP server that tracks newly created liquidity pools on Pancake Swap, providing real-time data for DeFi analysts, traders, and developers.
- [kukapay/uniswap-poolspy-mcp](https://github.com/kukapay/uniswap-poolspy-mcp) - An MCP server that tracks newly created liquidity pools on Uniswap across nine blockchain networks.


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
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) - Provide the latest cryptocurrency news to AI agents, powered by CryptoPanic.
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) - An MCP server that provides real-time and historical Crypto Fear & Greed Index data, powered by the Alternative.me.
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) - An Model Context Protocol (MCP) server for tracking cryptocurrency whale transactions using the Whale Alert API.


### 💬 <a name="social"></a>Social

Social MCP modules integrate with social platforms and protocols to enable identity management, messaging, and social graph interaction.

- [vidhupv/x-mcp](https://github.com/vidhupv/x-mcp) - An MCP server to create, manage and publish X/Twitter posts directly through Claude chat.
- [hanweg/mcp-discord](https://github.com/hanweg/mcp-discord) - An Model Context Protocol (MCP) server that provides Discord integration capabilities to MCP clients like Claude Desktop.
- [sparfenyuk/mcp-telegram](https://github.com/sparfenyuk/mcp-telegram) - The server is a bridge between the Telegram API and the AI assistants and is based on the Model Context Protocol.
