---
date: 2026-09-07
angle: Electrolytes & sports nutrition
---

# Volume Beats Chemistry: A New Heat-Cycling Study Undercuts the Sweat-Sensor Gold Rush

**TL;DR**
- A 2026 *European Journal of Applied Physiology* study on 11 trained cyclists found that replacing 80% of fluid losses (vs. 60%) produced an 8% faster time trial in the heat — with serum sodium matched between groups. The variable that moved performance was volume replaced, not sodium chemistry.
- At the same time, the sweat-sensing hardware category raised real capital in 2026: Onalabs closed over €9.3M (with FC Barcelona and Garmin as strategic partners) and PointFit landed a $10M valuation — both betting on inferring hydration/electrolyte status from sweat chemistry.
- Peer-reviewed validation of the two most mature sweat-sodium wearables, Flowbio and hDrop, still shows a systematic ~10 mmol/L bias against flame-photometry (the lab gold standard), with field accuracy estimated around 73-92% depending on device and metric.
- Individual sweat sodium concentration varies up to 10x across athletes (roughly 200 to 2,300+ mg/L), which is exactly the kind of person-to-person variability that makes inference-based correction hard.
- Net effect: a meaningful slice of 2026 hydration-tech capital is chasing a harder, noisier estimation problem (sweat chemistry) to influence a behavior — drink enough — that direct measurement already answers without needing to solve chemistry at all.

## The Research

The most interesting hydration finding to come out of sports science this year isn't about electrolytes — it's about what electrolytes *aren't* doing. In the new EJAP study, 11 male cyclists (mean age 35, VO₂max 58 ml/kg/min) rode 180 minutes at 90% of their first lactate threshold in 32°C heat and 50% humidity, then completed a work-matched time trial, twice: once replacing 60% of projected fluid losses, once replacing 80%. Sodium intake was individually prescribed in both conditions to land at the same serum sodium concentration, isolating fluid volume as the only variable that differed. The 80%-replacement condition — which kept body-mass loss under the commonly cited 2% dehydration threshold — produced an 8% faster time trial than the 60%-replacement condition, despite equivalent serum sodium. The deficit showed up in plasma volume and thermal strain, not electrolyte balance. In plain terms: matching your sodium doesn't rescue you from underdrinking, and the actual milliliters you get in your body still do most of the causal work.

That finding lands awkwardly next to where hydration-tech investment is actually going. Onalabs, the Barcelona-based sweat-sensor maker whose chest-strap Onasport was co-developed with FC Barcelona's innovation hub, closed a funding round of more than €9.3M this year, split between Spanish public innovation funds and private investors, with Garmin distribution as part of the go-to-market. PointFit, a Hong Kong-based lactate-and-sweat patch maker, took a strategic round valuing the company at $10M with ASICS Ventures among the backers. Both are chasing the same bet: that continuously reading sweat chemistry — sodium, lactate, conductivity — is the differentiated signal worth building hardware around.

The problem is that sweat chemistry is a genuinely hard measurement problem, and 2026's own validation literature says so. A Frontiers in Physiology study benchmarking the Flowbio wearable sweat sensor against flame photometry (the actual lab gold standard) in both dry and humid heat found a consistent ~10 mmol/L underestimate in sweat sodium — stable across conditions, but a real, unresolved bias, not the kind of within-device-noise a firmware update fixes. Comparative field data cited alongside it put Flowbio's field accuracy around 83% for sodium and 73% for fluid-loss estimation; hDrop, a competing sweat-rate-and-sodium patch, has reportedly closed the gap to around 92% on sodium as of this year but started from a lower baseline. None of this makes these devices useless — they're the best available instruments for sweat chemistry — but it does mean the category is still fighting a hard estimation problem with double-digit-percent error bars, layered on top of the fact that sweat sodium concentration itself varies roughly 10x between individuals (from ~200 to over 2,300 mg/L), largely for genetic reasons tied to sweat-duct sodium reabsorption. Correcting for both device bias and biological variance at once is the actual technical challenge these companies are raising capital to solve.

## Why This Matters for syp

This is a clean natural experiment for syp's positioning: the 2026 study that most directly moved the sports-science needle on heat performance isolated *fluid volume replaced* as the causal lever, independent of sodium — which is precisely the parameter syp's mass-change sensor measures directly and with commodity-scale-level precision, no chemistry required. Meanwhile a meaningful share of adjacent hydration-tech funding (Onalabs, PointFit) is being spent solving a much harder problem — inferring sweat chemistry accurately enough to correct for 10x individual variance — and still landing at 73-92% field accuracy against gold standard. There's a sharp content and fundraising narrative here: "the science says volume is what matters; we measure volume directly; the market is instead funding a chemistry-inference problem with a real, published accuracy gap." Worth a founder-note or investor-deck callout rather than a generic hydration-matters line.

## Sources

1. [Inadequate fluid replacement during prolonged cycling in the heat impairs time trial performance independent of serum sodium concentrations](https://link.springer.com/article/10.1007/s00421-026-06245-2) — European Journal of Applied Physiology, 2026
2. [Onalabs Raises Over €9.3 Million to Scale Its Continuous Health Monitoring Solutions](https://insider.fitt.co/press-release/onalabs-raises-over-e9-3-million-to-scale-its-continuous-health-monitoring-solutions/) — Fitt Insider, 2026
3. [Non-Invasive Lactate Sensor: PointFit PF-Sweat Patch](https://the5krunner.com/2026/02/26/non-invasive-lactate-sensor-sport-pointfit-pf-sweat-patch/) — The 5th Runner, February 2026
4. [Sweat sodium composition and sweat loss estimation through wearable sensors and predictive equations in dry and humid hot conditions](https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2025.1717275/full) — Frontiers in Physiology, 2025/2026
5. [Types of Sweat Tests Compared: Best for Athletes (2026)](https://hdroptech.com/types-of-sweat-tests/) — hDrop, 2026
6. [How to estimate how much sodium you lose in your sweat](https://www.precisionhydration.com/performance-advice/hydration/how-to-estimate-sweat-salt-loss/) — Precision Hydration
