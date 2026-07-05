# Investment Skills Manifest

This repository is the canonical source for Evan's investment research skills.

When a skill is invoked, read this manifest first, then read the corresponding `skills/<name>/SKILL.md` before producing analysis. Do not rely on compressed chat memory as the source of truth.

## Global Usage Rule

1. Identify the requested skill or infer the most relevant skill from the user's task.
2. Fetch `SKILLS_MANIFEST.md`.
3. Fetch the selected `skills/<name>/SKILL.md`.
4. Apply the skill exactly as written.
5. If the file cannot be fetched, state that the canonical file is unavailable and avoid pretending to run the skill.

## Skill Index

| Skill | Path | Use when |
|---|---|---|
| valuation-mapping | `skills/valuation-mapping/SKILL.md` | Analyze a stock's current market cap or price by reverse-engineering the implied revenue, profit, volume, ASP, ROE, order book, capacity, or product-cycle expectation. |
| industry-research | `skills/industry-research/SKILL.md` | Research an industry or theme such as glass substrate, ADC, peptides, MLCC, storage, robotics, CPO, semiconductor materials, or advanced packaging. |
| overseas-a-share-mapping | `skills/overseas-a-share-mapping/SKILL.md` | Translate overseas market moves, earnings, guidance, supply-chain news, or sector narratives into A-share implications. |
| horizontal-breakout | `skills/horizontal-breakout/SKILL.md` | Scan or evaluate stocks with long sideways bases, moving-average compression, volume breakout, and platform or previous-high resistance breaks. |
| narrative-shift-radar | `skills/narrative-shift-radar/SKILL.md` | Detect whether a sector narrative has shifted from old logic to new logic, especially before the change becomes consensus. |
| best-ticket-1450 | `skills/best-ticket-1450/SKILL.md` | Choose late-afternoon A-share trade candidates with T+1 risk/reward, buyability, liquidity, sector status, and tail-risk controls. |
| serenity-alpha | `skills/serenity-alpha/SKILL.md` | Convert news into testable alpha hypotheses by mapping observable demand changes to revenue/profit transmission and small-cap elasticity. |
| tam-adj-peg | `skills/tam-adj-peg/SKILL.md` | Judge whether a growth stock is cheap or expensive after adjusting PEG by TAM runway and business quality. |
| gf-dma-health-index | `skills/gf-dma-health-index/SKILL.md` | Score whether a stock's trend is supported by fundamental speed, DMA structure, price-DMA divergence, escape ratio, and estimate revisions. |

## Priority Rules

- For individual stock valuation: start with `valuation-mapping`; add `tam-adj-peg` if the stock is a growth stock or early-stage TAM story; add `gf-dma-health-index` if the question is about trend health or trade timing.
- For industry or theme research: start with `industry-research`; add `serenity-alpha` for event/news-driven leads; add `overseas-a-share-mapping` when overseas comparables are moving.
- For daily trading or scanning: use `horizontal-breakout`, `narrative-shift-radar`, and `best-ticket-1450` together.
- Current data is required for market prices, financials, forecasts, estimates, volume, sector moves, and news. Verify with current sources before making time-sensitive statements.
