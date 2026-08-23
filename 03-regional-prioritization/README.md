# Field Assignment 03: Regional Prioritization for Operational Investment

**Status:** Complete  
**Date:** August 2026  
**Glorystone Data Analytics Portfolio**

## Business Question
Which regions (and the stores within them) should Glorystone prioritize for operational improvement investment over the next 90 days, based on a balanced view of volume, fulfillment performance, customer experience, and revenue exposure?

## Key Findings
- North, Central, and South each carry ~24–25.5% of network revenue and similar order volume.
- Central and South lag meaningfully on readiness delay, on-time rate, fill rate, and completeness.
- The performance gap is highly concentrated in three stores:
  - **GS-09 (South)** — most severe operational pain (25.2 min delay, 6% on-time, 84.6% fill, 7.6% complete)
  - **GS-04 (Central)** — second-highest severity
  - **GS-11 (East)** — highest volume among underperforming stores
- Customer wait and abandonment show almost no meaningful store or regional variation (consistent with FA02).

## Priority Focus Areas (Next 90 Days)
1. **GS-09 (South)** — Primary focus. Highest operational severity.
2. **GS-04 (Central)** — Primary focus. Second-highest severity with meaningful volume.
3. **GS-11 (East)** — Secondary focus. Material volume + elevated pain.

## Recommended Actions
1. Conduct focused on-hand accuracy audits at GS-09 and GS-04 for high-volume and high-substitution items. Correct inventory records and adjust replenishment settings.
2. Review substitution detail reports and set explicit readiness and fill-rate targets with store leadership.
3. Hold structured working sessions with Team Leads at the three priority stores to surface floor-level obstacles.
4. Track weekly % of orders with readiness delay > 10 minutes and fill rate < 90% at these stores.

## Expected Impact & Success Criteria
| Metric | Current (Focus Stores) | 90-Day Target |
|--------|------------------------|---------------|
| Avg readiness delay | GS-09: 25.2 min / GS-04: 19.4 min | Both below 12 minutes |
| On-time readiness | GS-09: 6% / GS-04: 10% | ≥ 18% |
| Fill rate | GS-09: 84.6% / GS-04: 86.3% | ≥ 92% |
| Completeness | GS-09: 7.6% / GS-04: 10.7% | ≥ 25% |

Success is defined as measurable movement of GS-09 and GS-04 toward the network median on the four operational metrics while maintaining volume.

## Files
- `03_regional_prioritization.ipynb` — Full end-to-end analysis (feature engineering, regional & store summaries, rank-based prioritization score, recommendation)
- Source data: same network-wide order file used in FA01 and FA02

---
*This project demonstrates the shift from diagnosis to prioritization: clear business question → integrated metrics → transparent ranking → decision-ready recommendations with success criteria.*
