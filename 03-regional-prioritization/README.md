# Field Assignment 03: Regional Prioritization for Operational Investment

**Status:** In Progress  
**Date:** August 2026  
**Glorystone Data Analytics Portfolio**

## Business Question
Which regions (and the stores within them) should Glorystone prioritize for operational improvement investment over the next 90 days, based on a balanced view of volume, fulfillment performance, customer experience, and revenue exposure?

This project moves from pure diagnosis (FA01 and FA02) into prioritization. Leadership needs a clear, defensible answer to where limited attention and resources will produce the highest return.

## Scope
Same source data used in FA01 and FA02 (`glorystone_online_pickup_orders.csv`).  
Metrics reused and extended:
- Order volume and revenue exposure
- Readiness performance (delay, on-time rate)
- Fill rate / completeness
- Customer wait and abandonment

## Initial Regional Findings
The three largest regions (North, Central, South) each carry roughly 24–25.5% of network revenue and similar order volume. Performance, however, is not equal:

- **North** leads on readiness delay, on-time rate, fill rate, and completeness.
- **Central** and **South** lag meaningfully on every fulfillment metric while matching North on scale.
- Wait time and abandonment show almost no regional variation (consistent with FA02).

The performance gap inside Central and South is concentrated in specific stores (primarily GS-04 and GS-09), confirming the store-level outliers identified in FA01.

## Next Steps
1. Build store-level prioritization score that balances volume, performance, customer experience, and revenue exposure.
2. Rank regions and stores.
3. Recommend the top 2–3 focus areas for the next 90 days with expected impact and success measures.

## Files
- `03_regional_prioritization.ipynb` — End-to-end analysis (in progress)
- Source data remains the same network-wide order file used in prior assignments.

---
*This project demonstrates the shift from diagnosis to prioritization: clear business question → integrated metrics → ranked focus areas → decision-ready recommendations.*
