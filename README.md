# Partial Correlation-Based Connectedness: Extreme Dependence Among Commodities

> **Published in:** Energy Economics, Vol. 144 (2025), Article 108421
> **Authors:** Syed Jawad Hussain Shahzad · Elie Bouri · Sitara Karim · Perry Sadorsky

---

## What This Paper Is About

This paper proposes a new method — **partial correlation-based connectedness** — to study how 22 commodity markets are linked to each other under both normal and extreme market conditions, and examines what that means for portfolio construction.

It compares this approach against the widely used **Diebold-Yilmaz (GFEVD)** connectedness method and shows why accounting for the *sign* and *tail behavior* of correlations matters.

---

## Data

- **22 commodity futures** across 4 groups: Energy, Agricultural, Precious Metals, Industrial Metals
- **Period:** September 1, 2005 – June 5, 2024 (~4,895 daily observations)
- Covers major crises: Global Financial Crisis (2007–09), Oil Price Collapse (2014–16), COVID-19 (2020), Russia-Ukraine War (2022)

---

## Key Findings

1. **Better crisis detection** — The partial correlation approach spikes at the extreme lower quantile *before* major crises (GFC, COVID-19, Ukraine war), which the GFEVD approach fails to detect.

2. **Asymmetric tail dependence** — Lower-tail connectedness is consistently stronger than upper-tail, confirming that commodity markets co-crash more than they co-boom.

3. **Unstable structure during crises** — The connectedness ranking of commodities shifts significantly during turbulent periods, a feature invisible to the GFEVD approach.

4. **Industrial metals transmit; agricultural commodities receive** — Copper, Zinc, and Lead are the dominant net transmitters of shocks; Coffee, Rice, and Cocoa are the largest net receivers.

---

## Portfolio Strategy

The paper introduces the **Inverse FROM Connectedness Portfolio (IFCP)**, which underweights commodities with high spillover exposure and high volatility.

| Strategy | Sharpe Ratio | Volatility | Max Drawdown |
|---|---|---|---|
| Equally Weighted (EW) | 0.005 | 5.17% | −32.95% |
| Min Variance (minVar) | 0.286 | 5.74% | −32.03% |
| **IFCP** | **0.118** | **5.29%** | **−33.15%** |
| **IFCP (Lower Tail)** | **0.176** | **5.11%** | **−29.62%** |
| Min Connectedness (MCP) | 0.017 | 5.59% | −31.64% |

> IFCP outperforms MCP and most benchmarks on a risk-adjusted basis. Agricultural commodities receive the highest portfolio weight across all strategies due to their relative stability during crises.

---

## Why It Matters

- Correlation **sign** matters for portfolios — two negatively correlated assets show high connectedness under GFEVD but offer *more* diversification, not less.
- Partial correlations provide a more realistic picture of systemic risk in commodity markets, especially during crises.
- Useful for **investors, risk managers, and policymakers** monitoring commodity market stability.

---

## JEL Classification

`G11` — Portfolio Choice · `G15` — International Financial Markets · `Q43` — Energy and the Macroeconomy
