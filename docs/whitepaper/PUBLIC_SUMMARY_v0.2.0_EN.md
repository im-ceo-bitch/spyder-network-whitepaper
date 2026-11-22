# SPYDER NETWORK — Public Research Summary v0.2.0

**Draft prepared: 22 November 2026.** Publication timestamp will be assigned by the hosting service when posted. **This is a research proposal, not a mainnet launch, token offering or registered trademark.**

## Project identity
- **Spyder Network**: proposed blockchain and applications ecosystem.
- **SpyderChain**: proposed independent Layer-1 blockchain (previously discussed Rust / SpiderBFT / `spider1...` research implementation; not independently audited).
- **SpyderCoin (SPD)**: proposed native asset for transaction fees and, conditional on validated consensus, network economic security.
- **Spyder Wallet**: user-facing wallet. Spyder Messenger, Spyder ID and Spyder Terminal are additional proposed ecosystem products.

## Why create Spyder?
The design hypothesis is to make digital-asset interactions easier to understand and verify, connecting identity, contact, authorization and settlement without concealing financial risk. A new token does not by itself create demand. Product-market fit and safe infrastructure are prerequisites.

## Monetary design M-01 — proposed, NOT final
- Candidate lifetime maximum: **9,999,999,999 SPD**; this figure was previously discussed and remains under review.
- Proposal: 75% minted at audited genesis into publicly visible locked allocations; up to 25% emitted as declining validator rewards over 15 years, subject to consensus security research and a deterministic capped algorithm. This is not a statement about current supply.
- Proposed allocations as a share of max: community/developers 35%; validator security 25%; protocol treasury 15%; core contributors 10%; founders 5%; integrations 5%; security/public goods 5%.
- Illustrative security emission: normalized geometric decay factor 0.90 over 15 years, with approximately 314.8m SPD in year 1 and 185.9m in year 6; exact rounding, timing and slashing are unresolved.
- Initial fee-policy research candidate: 90% of base fees to validators, 10% to transparent protocol treasury, 0% burned. Validator priority fees require an audited implementation. Proposing a burn now would weaken the early security budget without evidence of economic benefits.
- Vesting: core contributors 4 years/12-month cliff; founders 6 years/24-month cliff; community allocations subject to documented, earned-distribution milestones. Nothing here is an existing allocation or wallet balance.

## Economic integrity
Native fees, validator stake and developer activity may create utility for SPD, but **supply caps, staking yield and token burning do not guarantee price appreciation**. USD-denominated user payments may be supported in stablecoins while sponsors acquire SPD for gas; the actual gas consumption remains real and may be economically small. Disclose fully diluted supply, circulating supply, locked supply, emissions, vesting, holder concentration and fee revenue separately. Address validator cost in low-volume scenarios.

## 2026–2032 research gates
1. Publish verifiable implementation and exact protocol commit.
2. Prove independent validators, liveness, consensus safety and transaction correctness.
3. Run public testnet and independently audit wallet, signing and consensus.
4. Verify gas economics, distribution, validator security budget, fee revenue and honest supply reports.
5. Approve final genesis and monetary parameters only after public review.
6. No sale, staking yield, listing or investment-return promise in this research phase.

## References
- Bitcoin monetary policy: https://bitcoin.org/en/halving
- Ethereum supply: https://ethereum.org/what-is-ether/supply/
- EIP-1559: https://eips.ethereum.org/EIPS/eip-1559
- Solana economics: https://solana.com/staking and https://solana.com/docs/core/fees
- Cosmos validator economics: https://github.com/cosmos/cosmos/blob/master/VALIDATORS_FAQ.md
- Cambridge security-budget research: https://www.jbs.cam.ac.uk/faculty-research/centres/alternative-finance/publications/funding-bitcoins-future-paying-for-security-as-the-block-subsidy-fades/
- Token float research: https://www.coingecko.com/research/publications/low-vs-high-float-crypto

**This short document is the English summary of the Russian research draft, not a certified translation or a final executable protocol specification.**
