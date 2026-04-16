<p align="center">
  <a href="https://fairco.in">
    <img src="https://avatars.githubusercontent.com/u/102275008?s=200&v=4" alt="FairCoin" width="120" />
  </a>
</p>

<h1 align="center">FairCoin</h1>

<p align="center">
  A decentralized cryptocurrency with <b>Masternodes</b>, <b>Coin Mixing</b>, and a <b>PoW/PoS hybrid</b> consensus.
  <br />
  Built for social and economic justice since 2014.
</p>

<p align="center">
  <a href="https://fairco.in">Website</a> ·
  <a href="https://academy.fairco.in">Academy</a> ·
  <a href="https://github.com/FairCoinOfficial/FairCoin/releases">Downloads</a> ·
  <a href="https://t.me/FairCoinOfficial">Telegram</a> ·
  <a href="https://twitter.com/FairCoin_">Twitter</a>
</p>

---

## What is FairCoin?

FairCoin (ticker **FAIR**) is an open-source cryptocurrency focused on fair distribution, privacy, and low-energy consensus. The project is community-led, fully open-source, and maintained under this organization.

| | |
|---|---|
| **Ticker** | FAIR |
| **Algorithm** | Quark |
| **Consensus** | PoW + PoS hybrid |
| **Block time** | 120 s |
| **Max supply** | 33,000,000 FAIR |
| **Masternode collateral** | 5,000 FAIR |
| **Address prefix** | `F` (mainnet) / `T` (testnet) |

Full spec, block rewards, and network ports: see [FairCoin Core README](https://github.com/FairCoinOfficial/FairCoin#coin-specifications).

---

## Ecosystem

### Protocol
| Repo | Description | Stack |
|---|---|---|
| [**FairCoin**](https://github.com/FairCoinOfficial/FairCoin) | Reference node & wallet (`faircoind`, `faircoin-qt`, `faircoin-cli`) | C++ |
| [**faircoin-seeder**](https://github.com/FairCoinOfficial/faircoin-seeder) | DNS seeder powering `seed1.fairco.in` / `seed2.fairco.in` | C++ |

### Run a node
| Repo | Description | Stack |
|---|---|---|
| [**FAIRNode**](https://github.com/FairCoinOfficial/FAIRNode) | Docker image for a full node (Debian 12, minimal) | Docker |
| [**FAIRNodeDesktop**](https://github.com/FairCoinOfficial/FAIRNodeDesktop) | Cross-platform desktop node with GUI | Electron + Vite + React |

### Wallets
| Repo | Description | Stack |
|---|---|---|
| [**FAIRWallet**](https://github.com/FairCoinOfficial/FAIRWallet) | SPV wallet for Android, iOS, Windows, macOS, Linux — HD, BIP39/32/44, FastSend, masternodes, BIP38 | Expo 55 / React Native 0.83 / TypeScript |

### Libraries (TypeScript SDK)
Published to npm under the [`@fairco.in`](https://www.npmjs.com/org/fairco.in) scope.

| Repo | Package | Description |
|---|---|---|
| [**faircoin-core**](https://github.com/FairCoinOfficial/faircoin-core) | [`@fairco.in/core`](https://www.npmjs.com/package/@fairco.in/core) | Protocol primitives — BIP32/39/44 HD wallets, tx build/sign, P2PKH, Quark, BIP38, BIP21. Zero React Native deps. |
| [**faircoin-rpc-client**](https://github.com/FairCoinOfficial/faircoin-rpc-client) | [`@fairco.in/rpc-client`](https://www.npmjs.com/package/@fairco.in/rpc-client) | Zero-dependency JSON-RPC client for `faircoind`. Node 20+. |

### Services & tools
| Repo | Description | Stack |
|---|---|---|
| [**Explorer**](https://github.com/FairCoinOfficial/Explorer) | Public block explorer with MongoDB caching | Next.js 14 + Tailwind |
| [**FairRPCAPIServer**](https://github.com/FairCoinOfficial/FairRPCAPIServer) | REST API layer over FairCoin JSON-RPC | Node.js + Express |
| [**faircoin-web-proxy**](https://github.com/FairCoinOfficial/faircoin-web-proxy) | Lightweight web proxy for RPC endpoints | JavaScript |

---

## Get started

**Users** → download a wallet from [FAIRWallet releases](https://github.com/FairCoinOfficial/FAIRWallet/releases) or the [FairCoin Core releases](https://github.com/FairCoinOfficial/FairCoin/releases).

**Node operators** → run [FAIRNode](https://github.com/FairCoinOfficial/FAIRNode) (Docker) or [FAIRNodeDesktop](https://github.com/FairCoinOfficial/FAIRNodeDesktop) (GUI). Masternodes require 5,000 FAIR collateral — see [FairCoin Core docs](https://github.com/FairCoinOfficial/FairCoin/tree/main/doc).

**Developers** → build on FairCoin with the TypeScript SDK:
```sh
bun add @fairco.in/core @fairco.in/rpc-client
```
Or integrate via [FairRPCAPIServer](https://github.com/FairCoinOfficial/FairRPCAPIServer) / query the [Explorer](https://github.com/FairCoinOfficial/Explorer) directly. Report issues in the relevant repo.

**Learners** → visit [FairCoin Academy](https://academy.fairco.in).

---

## Contributing

All repos are open to contributions. Before opening a PR:

1. Check existing issues and discussions on the target repo.
2. Follow the repo's contribution guide and code style.
3. Sign your commits where applicable.
4. For protocol-level changes to [FairCoin](https://github.com/FairCoinOfficial/FairCoin), open a discussion first.

Security issues: email **team@fairco.in** — do not open public issues for vulnerabilities.

---

## Community

- **Website** — <https://fairco.in>
- **Academy** — <https://academy.fairco.in>
- **Telegram** — <https://t.me/FairCoinOfficial>
- **Twitter / X** — [@FairCoin_](https://twitter.com/FairCoin_)
- **Email** — team@fairco.in

<p align="center"><sub>FairCoin is free software released under the MIT License. Use at your own risk.</sub></p>
