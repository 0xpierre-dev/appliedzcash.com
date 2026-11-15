# appliedzcash.com

Mark bought appliedzcash.com on Nov 14, 2026. The site publishes Shielded Labs' work on building apps on Zcash: near-programmability with today's shielded protocol, and the patterns that make it work.

## Theme

Zcash has no smart contracts. Apps can still bind data and rules to shielded notes and let anyone verify them from chain data. The site teaches these patterns and shows working systems.

## Source material

| Topic | Where |
|---|---|
| Bound notes: data hashed into a zero-value note's `rseed`, so ZIP 212 derives ψ and rcm and standard wallets still decrypt the note | `zips/draft-shieldedlabs-bound-notes.md` in the Zodiac repo; X article draft (artifact "Bound Notes Article", https://claude.ai/artifact/MQDEGNCLnDxy7p7vVDf552); artifact "SRA on Bound Notes" (https://claude.ai/artifact/5kzFSdMMoV7qNiSZ7K5bdT) |
| Zodiac Markets: futarchy decision markets on Zcash testnet, verifiable checks V1 to V7, Lean-proved market math | `~/Projects/Zcash-Futarchy` (`README.md`, `DESIGN.md`, `BRIEF.md`, `docs/adr/`) |
| ZcashNames: the origin of the binding pattern (Julian, GitHub craftsoldier) | `/Users/mark/wiki/wiki/zcashnames.md`, `zns-verify.md` |
| Polite actions: every wallet trial-decrypts every action, so apps keep their action count low (ADR 5: one note per epoch) | `docs/adr/0005-one-note-per-epoch.md` |
| Builder support: `add_output_with_rseed` in orchard, now built from a fork, upstream PR pending | Zodiac `BRIEF.md`, craftsoldier/orchard#3 and #4 |
| Market and app landscape | `/Users/mark/wiki/wiki/zcash-app-opportunity-2026.md`, `zodiac-markets.md`, `openzcash.md` |

## Constraints

- The Zodiac repo (ShieldedLabs/zodiac) is **private**. Mark decides what from it goes public.
- The Zodiac mainnet plan awaits team review. Keep it off the site until Mark clears it.
- The ZcashNames mention in the article waits on Julian's check.
- Never name the round 6 testers.
- Style: no em-dashes, no explanation by negation, short active sentences.

## Now

- [ ] Plan the site: audience, sections, first pages, stack and hosting. Ask Mark before choosing.
