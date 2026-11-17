# Screening Checklist (pre-trade, per CA)

Research and process support only, not financial advice. You place every trade yourself. Never share keys or seed phrases with any tool or site.

Legend: **A** = Axiom shows it natively · **F** = Fomo shows it natively · **T** = needs a free tool (Solscan, RugCheck, Bubblemaps, DexScreener). Check what each app currently shows; layouts change.

Any hard fail = skip. Don't "make an exception".

| # | Check | Pass looks like | Where |
|---|-------|-----------------|-------|
| 1 | Mint authority renounced | Disabled/none | A (Pulse badge), T (RugCheck, Solscan) |
| 2 | Freeze authority renounced | Disabled/none | A, T (RugCheck) |
| 3 | LP burned or locked | Burned, or locked with a long unlock date | A (pre-migration: bonding curve has no LP to pull), T (RugCheck) |
| 4 | Top-10 holder share | Low, excluding LP/bonding curve address; one wallet with a big chunk = fail | A, F, T (Solscan, Bubblemaps) |
| 5 | Dev holding / dev history | Dev holds little or sold; dev hasn't launched rugs before | A (dev %), T (Solscan wallet history) |
| 6 | Sniper / bundler share | Low; many wallets buying in the same block = bundled supply | A (sniper/bundle %), T (Bubblemaps) |
| 7 | Fresh-wallet clusters | Few new wallets funded by the same source | T (Bubblemaps links, Solscan funding trace); A shows fresh-wallet % on some views |
| 8 | Liquidity vs market cap | Enough liquidity that you can exit your size with low slippage | A, F, T (DexScreener) |
| 9 | Migration status | Know which stage it's in: bonding curve (New Pairs), near-migration, or migrated; check that the pool and LP are what you expect after migration | A (tabs) |
| 10 | Wash-traded volume | Volume matches unique traders/holders; no repeating same-size buys and sells | A (txns, traders), T (Solscan tx list, Bubblemaps) |
| 11 | Twitter/social account | Account is not brand new, followers look human, history predates the coin; no mass-bot replies | A (social tracker), manual check on X |
| 12 | Copy-paste / rug patterns | Name, ticker or image copied from a recent runner; website is a template; the same dev wallet or image has launched before | T (DexScreener search by name, Solscan) |

## Quick rug-pattern flags
- Bundled launch (many wallets, same block) plus a low-follower account.
- Holders are all fresh wallets with similar balances.
- Dev sells right after migration.
- Price pumps on tiny liquidity with few unique buyers.
- Sudden "Telegram/X exists only since today" story.

## Before you buy
- [ ] Hard fails: none
- [ ] Size follows `Risk Rules.md`
- [ ] Exit plan written down (see journal)
- [ ] I'm not tilted or chasing a missed move
