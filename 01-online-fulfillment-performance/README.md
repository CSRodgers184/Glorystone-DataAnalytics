# Field Assignment 01: Online Grocery Fulfillment Performance Review

**Status:** Complete  
**Date:** August 2026  
**Glorystone Data Analytics Portfolio**

## Business Question
Which stores show the clearest operational friction in online order fulfillment, and what specific actions should Glorystone take in the next 60–90 days?

## Key Findings
- Operational friction is highly concentrated in **GS-09** and **GS-04**.
- These two stores run **14–17 minutes slower** on average readiness delay than the rest of the network.
- They also show meaningfully lower fill rates and higher substitution rates.
- The delay problem is present across most of the operating day (not limited to a single peak hour).

## Priority Actions (60–90 days)
1. Conduct a focused on-hand accuracy audit at GS-09 and GS-04 for the highest-volume and highest-substitution items. Correct inventory records and adjust replenishment settings where systemic discrepancies are found.
2. Pull a substitution detail report for both stores to identify the specific items most frequently substituted. Prioritize those items for inventory correction and supplier reliability checks.
3. Hold a structured working session with the Team Leads at GS-09 and GS-04. Share the delay and fill-rate data, set clear readiness targets, and surface the operational obstacles they are seeing on the floor.

## Expected Impact
Improving on-hand accuracy should raise fill rates and reduce substitution volume. Combined with clearer targets and input from the store teams, average readiness delay at these two stores is expected to move closer to the network average within 60–90 days.

## Files
- `01_fulfillment_performance_analysis.ipynb` — Full end-to-end analysis
- `data/glorystone_online_pickup_orders.csv` — Source data (8,500 orders)

---
*This project demonstrates end-to-end operational analytics: clear business question → data cleaning & feature engineering → diagnostic summary → focused deep dive → specific, prioritized recommendations.*
