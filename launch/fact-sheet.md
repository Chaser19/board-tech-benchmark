# Launch fact sheet: approved figures and guardrails

Every figure below is taken from the scored dataset embedded in the published site (`index.html`, data build 2026-08-11). Use these numbers, and only these, in social posts, the Substack, and any press material. If the dataset is rebuilt, re-check this sheet before posting.

## Headline figures

| # | Figure | What it means | Source field |
|---|---|---|---|
| 1 | **99.8% vs 9.9%** | 99.8% of boards own technology risk somewhere; 9.9% own any part of the innovation portfolio | `agg.domains[].owned_any` |
| 2 | **94%** | Share of boards whose risk-minus-value gap is positive (they oversee tech risk more closely than tech value) | `agg.gap_positive_pct` |
| 3 | **0.85 vs 0.25** | Mean score (0–3 scale) for risk-oversight domains vs value-creation domains, roughly 3.4× | `agg.assurance_mean`, `agg.value_mean` |
| 4 | **27.4% vs 2.9%** | Boards that assign AI governance to a board body vs AI as competitive advantage, roughly 9× | `agg.subelements` |
| 5 | **1.3%** | Boards that own AI productivity | `agg.subelements` |
| 6 | **29.1% / 2.7%** | Boards that own any part of AI / boards that show AI oversight actually exercised (cadence, named owner, or a decision) | `agg.domains` (AI) |
| 7 | **45%** | Fortune 500 companies with a confirmed dedicated technology or innovation committee (208 of 458 scored) | `scan.adoption_pct` |
| 8 | **38%–51%** | Adoption range across Fortune rank bands: no size gradient | `scan.band_stats` |
| 9 | **65% vs 21%** | Of companies with a tech committee, share still routing cyber oversight to Audit vs to the tech committee | `scan.routing.adopters` |
| 10 | **0.46 vs 0.21** | Mean value-creation score where a committee charter was read vs not: more than double | `agg.charter` |
| 11 | **3 of 445** | Boards classified at the top maturity level (Leading) | `agg.maturity_counts` |
| 12 | **0%** | Boards that own innovation networks; 0.2% own new services | `agg.subelements` |

## The method in one line

446 large-cap U.S. boards (468 read, 22 excluded for extraction failures), 6 domains, 20 topics, each score traced to a quoted sentence in a 10-K, proxy, or committee charter.

## Supporting figures

- Cybersecurity: 99.8% owned, 75.3% exercised (named executive plus stated cadence).
- Data privacy owned by 49.6%; operational resilience by 17.5%.
- Emerging technologies is the strongest value domain: 46.4% own some part, driven by "strategic implications" (41.7%).
- Most common committee names: Technology (79), Science & Technology (39), Cybersecurity (14), Innovation (13).
- Charter coverage: 75 of 446 companies (17%).

## Guardrails (do not break these in any post)

1. **No individual company scores.** The per-company explorer is unverified working data. Never name a company with its score, rank, or level. Do not post screenshots of the explorer.
2. **Call every score a floor.** Disclosure is a proxy for behaviour; absence in a filing is not absence of oversight. Say "documented ownership" or "in their filings", not "boards don't govern X".
3. **No causal claim about committee structure.** Standing-committee boards score higher, but they also have far higher charter coverage (66% vs 3%). Do not post "tech committees make boards better".
4. **The shape is the claim, not the decimals.** Inter-rater reliability is not yet established. Prefer round framings ("about 1 in 10", "roughly 9×") in hooks, and keep exact figures for the body.
5. **Not a population estimate.** It covers large-cap U.S. filers. Don't generalise to "all companies" or "boards everywhere".
6. **Avoid "ad hoc" or level-5 language.** The maturity scale is 1–4 since 27 Jul 2026.
