### `user@dark-forest:~# whoami`

```ini
[Identity]   Roman J. (MEV Searcher)
[Mission]    Extract Maximal Extractable Value (MEV)
[Target]     EVM Mempool & Flashbots Relay
[Status]     Scanning pending transactions...
```

---

### 🏴‍☠️ Searcher Toolkit

I build bots to compete in priority gas auctions (PGA) and bundle markets.

| Component | Tech | Purpose |
| :--- | :--- | :--- |
| **Execution** | **Rust / Axum** | Low-latency bundle simulation & relay interaction |
| **Analysis** | **Python** | Offline mempool replay & pattern detection |
| **Strategy** | **TypeScript** | Sandwiching & liquidation logic |
| **Infra** | **Go** | Fee oracle & node connectivity |

---

### 💀 Offensive Research (Public Repos)

Tools for analyzing and simulating MEV opportunities:

* **[`flashbots-bundle-executor-sim`](https://github.com/RomanJ89/flashbots-bundle-executor-sim)**
    * *Local relay mock for testing bundle submission without mainnet risk.*
* **[`mev-simlab`](https://github.com/RomanJ89/mev-simlab)**
    * *Discrete-event simulator for block building and fee dynamics.*
* **[`mempool-replay-detector`](https://github.com/RomanJ89/mempool-replay-detector)**
    * *Forensic tool to detect sandwich attacks in historical data.*
* **[`priority-fee-oracle`](https://github.com/RomanJ89/priority-fee-oracle)**
    * *Statistical oracle for optimal gas bidding strategies.*
* **[`bundle-auction-lab`](https://github.com/RomanJ89/bundle-auction-lab)**
    * *Modeling the builder auction selection process.*

---

### 📡 Bot Status

```diff
+ [CONN] Connected to 4 relays
+ [PING] 12ms to block builder
! [WARN] High contention detected in pool 0x...
```

> *"The forest is dark and full of terrors."*
