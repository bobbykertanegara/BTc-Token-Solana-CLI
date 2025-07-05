# Bobby The Cat ($BTc) — Official Token Repository

**$BTc** is a meme-inspired charity token deployed on the **Solana** blockchain, representing a unique combination of digital culture, community-driven impact, and Web3 innovation.

## 🔗 Token Information

- **Token Name:** Bobby The Cat
- **Symbol:** $BTc
- **Mint Address:** `BoBBYtpE2kpAJwh5TPPky72KND2cWmtdYa63bqo2yiKs`
- **Total Supply:** 8,888,888,888 BTc
- **Decimals:** 9
- **Token Standard:** SPL (Solana Program Library)
- **Explorer Link:** [Solana.fm](https://solana.fm/address/BoBBYtpE2kpAJwh5TPPky72KND2cWmtdYa63bqo2yiKs)

---

## 🛡️ Token Immutability

We have enforced **full immutability** using the standard Solana CLI procedure. Below are the security steps applied:

- `Mint Authority` revoked permanently
- `Freeze Authority` revoked permanently
- `Metadata` initialized once and cannot be re-edited
- `Token supply` locked at creation with no further minting possible

📄 View full immutability declaration:  
[BTc_Token_Immutability_Declaration.pdf](./BTc_Token_Immutability_Declaration.pdf)

Metadata URI (IPFS):  
`https://ipfs.io/ipfs/bafybeiasfj6xdy3a6ku2v6f33irwhdbqvkldbuygera2437b7foyzwrqaq/btcmetadata.json`

---

## 🔒 Locked Token Allocations

We noticed that some platforms may incorrectly display our tokens as "unlocked." Please rest assured that our tokens are **properly locked** according to our official tokenomics.

You can verify lock status through:

🔗 [RugCheck](https://rugcheck.xyz/tokens/BoBBYtpE2kpAJwh5TPPky72KND2cWmtdYa63bqo2yiKs)  
🔗 [Solana Explorer](https://explorer.solana.com/address/BoBBYtpE2kpAJwh5TPPky72KND2cWmtdYa63bqo2yiKs)

### ✅ Breakdown of Locked Allocations:

| Category                | Allocation | Lock Link |
|------------------------|------------|-----------|
| CEX Liquidity          | 15%        | [🔗](https://share.google/fOB9Ix7h42U7lazBP) |
| Staking                | 10%        | [🔗](https://share.google/4hi8bTZEM0aGQlqlK) |
| Private Sale           | 10%        | [🔗](https://share.google/FvZDN86F1QTlo1Rx0) |
| Team Vesting           | 5%         | [🔗](https://share.google/nBok3R3anS1YTdCx0) |
| Airdrop & Community 1  | 4%         | [🔗](https://share.google/pWiqmYDpbg7Id6JcV) |
| Airdrop & Community 2  | 3%         | [🔗](https://share.google/LmWv5KAcONctsdXxd) |
| Airdrop & Community 3  | 3%         | [🔗](https://share.google/XOWOTecZWhGeGI8j6) |
| Charity 2              | 2%         | [🔗](https://share.google/t6VogU3yTYUKWZJVd) |
| Charity 3              | 2%         | [🔗](https://share.google/NHd5zpQh3k95opcIf) |
| Charity 4              | 2%         | [🔗](https://share.google/QkKqGzJIWq0epn8hV) |
| Charity 5              | 2%         | [🔗](https://share.google/7LjhTbmRAHfRkmMhf) |

---

## 📚 Commands Used via Solana CLI

We deployed and locked $BTc using the following commands:

```bash
# Create vanity wallet
solana-keygen grind --starts-with BoBBY:1

# Create token
spl-token create-token --decimals 9

# Disable mint authority
spl-token authorize <MINT> mint --disable

# Disable freeze authority
spl-token authorize <MINT> freeze --disable

# Initialize Metadata (only once)
spl-token-2022 initialize-metadata <MINT> --uri <IPFS_URI> --name "Bobby The Cat" --symbol "BTc"


💬 Community
Website: https://bobbythecat.io

Twitter: https://twitter.com/Bobby_Ktngr

Telegram: https://t.me/BobbyTheCat_OG

📢 Disclaimer
This repository is for transparency purposes and technical verification. We welcome blockchain enthusiasts, token reviewers, and community members to verify our on-chain claims and share feedback.
