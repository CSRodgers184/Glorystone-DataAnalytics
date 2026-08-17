# Field Assignment 01: Online Grocery Fulfillment Performance Review

**Glorystone Data Analytics Portfolio**  
**Status:** In Progress  
**Date Started:** 17 August 2026

## Business Question
Which stores (or store groups) show the clearest operational friction in online order fulfillment, and what specific actions should Glorystone take in the next 60–90 days?

## Dataset
- **File:** `data/glorystone_online_pickup_orders.csv`
- **Orders:** 8,500
- **Period:** 1 Nov 2025 – 30 Apr 2026
- **Stores:** GS-01 to GS-12 across North, Central, South, East, and West regions

### Columns
| Column | Description |
|--------|-------------|
| order_id | Unique order identifier |
| store_id | Store code (GS-01 … GS-12). Some missing values present. |
| region | Geographic region |
| order_datetime | Customer order placement time |
| promised_ready_datetime | Promised ready-for-pickup time |
| actual_ready_datetime | Actual ready-for-pickup time |
| pickup_datetime | Customer pickup time (null = no-show / not yet picked) |
| items_ordered | Items in original order |
| items_fulfilled | Items actually provided |
| substitution_count | Number of substitutions |
| is_complete | True if fully fulfilled with zero substitutions |
| order_value | Approximate order value ($) |

## Analysis Focus
- Readiness delay (actual vs promised)
- Fill / completeness rate
- Substitution rate
- No-show rate
- Performance by store, region, hour of day, day of week
- Prioritized operational recommendations

## Deliverables
- Clean Jupyter notebook with full end-to-end analysis
- Supporting charts and summary tables
- Clear, prioritized recommendations for operations leadership

---
*This is a portfolio project demonstrating end-to-end operational analytics for a Domain Specialist role.*
