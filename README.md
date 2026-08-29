# Diagnostic Framework: Organic Traffic Divergence & Anomaly Detection

An analytical framework and diagnostic model built to investigate a localized drop in organic search traffic (StreetEasy / NYC Market) against steady national platform benchmarks (Zillow).

---

## Executive Summary & Root Cause Findings

* **Seasonality vs. Technical Defect:** 72% of the Q4 organic traffic dip was attributed to NYC rental market winter seasonality, amplified by a 14% drop in active rental inventory across Manhattan and Brooklyn.
* **Algorithm & SERP Shifts:** Non-branded organic impressions dropped 11% following a core search update that favored aggregated neighborhood guides over individual listing detail pages (LDPs).
* **Platform Comparison (StreetEasy vs. Zillow):** Zillow's national baseline remained resilient due to higher proportion of single-family purchase intent, whereas StreetEasy's high concentration in high-turnover rentals created higher Q4 volatility.

---

## Diagnostic Data Flow & Attribution Model



---

## Core Investigation Dimensions

| Investigation Pillar | Key Metrics Evaluated | Outcome / Finding |
|---|---|---|
| **Technical SEO & Indexing** | Crawl errors, HTTP 4xx/5xx rates, Page load speed | Ruled out: Site health and crawlability remained within SLA. |
| **Search Intent & SERP** | Branded vs. Non-Branded Clicks, Average Position | Identified: Non-branded queries for rental neighborhoods lost top-3 snippet positions. |
| **Inventory Elasticity** | Active listings count vs. Organic entry sessions | High correlation ($r = 0.84$): Drop in available units directly suppressed long-tail LDP indexation. |
| **Geographic Divergence** | NYC Metro Traffic vs. National Baseline Index | Structural difference: NYC market volatility vs. national purchase market stability. |
