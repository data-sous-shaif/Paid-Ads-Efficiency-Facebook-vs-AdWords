# Digital Advertising Optimization – Executive Summary

## 1. Business Problem

We ran daily advertising campaigns for one full year (365 days) across two platforms:
- **Facebook Ads**
- **Google AdWords**

The goal of this analysis is to answer a simple business question:

> **How should we allocate advertising budget to maximize conversions while controlling costs?**

This requires comparing not just volume (clicks, conversions), but **cost efficiency, consistency, and predictability** across platforms.

---

## 2. Data Overview

- Granularity: **Daily**
- Time span: **365 days**
- Platforms analyzed:
  - Facebook Ads
  - Google AdWords
- Metrics available:
  - Views (Impressions)
  - Clicks
  - Conversions
  - Total Cost
  - CTR (Click-Through Rate)
  - Conversion Rate
  - CPC (Cost per Click)

All derived metrics (CTR, Conversion Rate, CPC) were validated for internal consistency before analysis.

---

## 3. Key KPIs

### Core Performance Metrics
- **CTR (Click-Through Rate)** – Traffic quality
- **Conversion Rate** – Landing page + intent quality
- **CPC (Cost per Click)** – Traffic acquisition efficiency

### 🎯 North Star Metric
**Cost per Conversion**

> Cost per Conversion directly ties advertising spend to business outcomes and enables a fair comparison across platforms with different traffic volumes.

---

## 4. High-Level Findings

### Performance
- Both platforms consistently generate conversions on a daily basis.
- Facebook generally produces **higher daily conversion volume**, while AdWords shows **more stable performance on certain periods**.

### Cost Efficiency
- Cost per Conversion varies significantly day to day, highlighting the importance of **averages vs volatility**.
- Periods of low CPC do not always translate into low Cost per Conversion, reinforcing the need to optimize for outcomes, not clicks.

### Consistency vs Scale
- Facebook benefits from scale and volume.
- AdWords provides more controlled and predictable performance during specific windows.

---

## 5. Statistical & Modeling Insights (Summary)

- A/B testing was used to compare mean daily conversions between platforms.
- Effect sizes were calculated to understand **practical impact**, not just statistical significance.
- Regression models showed a strong relationship between clicks and conversions on both platforms, with differing efficiencies.

These results support using **both platforms strategically**, rather than treating the decision as binary.

---

## 6. Business Recommendation

### Budget Allocation Strategy
- **Primary allocation:** Facebook Ads  
  - Best suited for scaling conversions efficiently.
- **Secondary allocation:** Google AdWords  
  - Ideal for stable, intent-driven traffic and risk balancing.

### Tactical Guidance
- Monitor **Cost per Conversion daily**, not just CPC or CTR.
- Reallocate spend dynamically during periods where one platform shows sustained efficiency.
- Use regression-based forecasts to estimate expected conversions before increasing spend.

---

## 7. Risks & Limitations

- This analysis is based on **observational data**, not randomized experiments.
- External factors (seasonality, competition, creative changes) are not explicitly modeled.
- Attribution is platform-level; cross-channel effects are not captured.

---

## 8. Future Improvements

- Run controlled A/B budget experiments for causal validation.
- Implement multi-touch attribution modeling.
- Use Bayesian methods for uncertainty-aware budget planning.
- Introduce time-series forecasting to anticipate performance shifts.

---

## 9. Final Takeaway

**Optimizing digital advertising is not about choosing one platform over another — it’s about allocating spend based on cost-efficient conversions, consistency, and risk tolerance.**

Cost per Conversion should remain the guiding metric for all future campaign decisions.
