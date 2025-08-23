# 🚗 ROC Coin (Road Owners Coin)

![ROC Logo](https://i.postimg.cc/MTffMpZQ/roc-logo-256x256-1.png)

# ROC Coin (ROC) — Official Docs

**Network:** BNB Smart Chain (BEP-20)  
**Decimals:** 18  
**Transfer Tax:** 0%  
**Whitepaper v2:** [ROC_Coin_Lite_Whitepaper_v2.pdf](./ROC_Coin_Lite_Whitepaper_v2.pdf) 
**Archived (deprecated) v1:** [ROC_Coin_Lite_Whitepaper 1.pdf](./ROC_Coin_Lite_Whitepaper%201.pdf)


---

## What is ROC Coin?
ROC Coin is a **community token** for the Road Owners Club. It powers membership perks, rewards, and engagement.  
**No ICO/IEO. No investment promises.** Our focus is on transparent, utility-based community usage.

---

## Contract Information

- **Contract Address (v2):** `0x2778aC04A763C612d102412D57BeF3AB0adF140D`
- **Explorer (BscScan):** https://bscscan.com/token/0x2778aC04A763C612d102412D57BeF3AB0adF140D
- **Network / Standard:** BNB Smart Chain — BEP-20
- **Decimals:** 18
- **Transfer Tax:** 0%
- **Deprecated v1:** `0xcd5a5Ef60Fea89299A2e062ee18721111001A4Ff` *(do not use)*
---

## Version History
- **V1 (deprecated):** Fixed 1,000,000 supply; never distributed; no holders.  
- **V2 (current):** **Mintable (uncapped)** with burn support; 0% transfer tax; 18 decimals.

> V2 clarifies long-term utility by allowing mint-on-demand for club growth while enforcing strict policies and transparency.

---

## Tokenomics (v2)

**Supply Model:** Mintable (uncapped) for long-term club growth  
**Mint Authority:** 2-of-3 multisig (Treasury only; mints go to Treasury first)  
**Mint Cap:** New mints ≤ **10% of circulating supply** per rolling 12 months  
**Burn:** Contract burn / 0x...dEaD; target ≈ **10% of net new annual mints**  
**Distribution:** Airdrops (500 ROC/member), rewards & events, time-locked Treasury  
**Taxes:** 0% transfer

### Minting Policy
- **Authority:** A **2-of-3 multisig Treasury** is the **only minter**.
- **Destination:** All new mints go to **Treasury** first (never to individuals directly).
- **Rate-Limit (Anti-Inflation Guardrail):**  
  In any rolling 12-month period, **New Mints ≤ 10% of CS** measured at the start of that window.  
  *Example:* If CS = 1,000,000 ROC on Jan 1, then total new mints from Jan 1–Dec 31 should be ≤ 100,000 ROC.
- **Change Management:** Any change to mint policy or caps is publicly announced with a **7-day cooldown** before taking effect.
- **Transparency:** Every mint txid, amount, and date are published below in **Mint/Burn Ledger** and are visible on-chain.

### Burn Policy
- **Mechanisms:**  
  - Contract burn (e.g., `burn(amount)` / `burnFrom(address, amount)`) **or**  
  - Proof-of-burn by sending to `0x000000000000000000000000000000000000dEaD`.
- **Objective:** Offset inflation from new mints and aim for a **slight deflationary drift** over time.
- **Target Burn Rate:** Treasury **targets burning ≈ 10% of net new annual mints** (same 12-month measurement window).
- **Reporting:** All burn txids and cumulative totals are published in the **Mint/Burn Ledger**.

### Allocations & Flows (Utility-only)
- **Member Airdrop:** 750 ROC per approved member (mint-on-demand from Treasury).
- **Rewards & Events:** Grants for community activities.
- **Treasury (with optional timelocks):** Operations and future utility.
- **(Future) Liquidity:** 0% initially; if enabled later, a public notice and separate policy will be published.

---

## Governance & Safety
- **Multisig:** All mint/burn/treasury actions require **2-of-3 approvals**.
- **Timelock (recommended):** 24–48 hours on mint transactions for public monitoring.
- **No Trading Taxes:** 0% to reduce friction and attack surface.
- **Renouncing/Freezing:** If the community opts for a fixed-supply regime later, minter rights can be revoked/renounced, and all usage will rely on existing Treasury balances.

---

## Mint/Burn Ledger (Transparency)
> We publish a running log of all mint and burn transactions here.

| Date (UTC) | Action | Amount ROC | Txid | Notes |
|---|---:|---:|---|---|
| TBA | Mint |  |  |  |
| TBA | Burn |  |  |  |

---
## Roadmap

**Phase 1 — Launch & Club Integration**  
Deploy v2, verify on BscScan, publish whitepaper & tokenomics.  
Mint member airdrops (within cap); start public Mint/Burn ledger; initial policy burn.

**Phase 2 — Merchandise Payments**  
Enable ROC on official store.  
Monthly burn **10–25%** of ROC received by store wallet (post-refunds).

**Phase 3 — DEX & Partners**  
Evaluate DEX liquidity and integrations (no price-support mints).  
Optional buy-back-and-burn from merch/partner proceeds.

**Phase 4 — NFT Utilities**  
NFT perks/membership (no investment claims).  
Burn ~**20%** of ROC paid to mint NFTs (or buy-back-and-burn). 

## Disclaimers
ROC Coin is a **community utility token**. It is **not** an investment and offers **no expectation of profit**. No ICO/IEO.  
Participation should comply with applicable laws and regulations.
public exchanges yet.
