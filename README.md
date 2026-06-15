# Hospital Supply Chain Performance Analysis — Jan 2024 to Dec 2025

> Two-year transactional audit of **$58.2 M** in procurement across 8 suppliers, 10 departments, and 8 product categories — surfacing delivery failures, supplier risk concentration, inventory exposure, and seasonal demand patterns.

---

## At a glance

| Metric | Value | Signal |
|---|---|---|
| Total spend (2024–2025) | $58.2 M | — |
| Total transactions | 30,050 | — |
| **On-time delivery rate** | **46.9 %** | 🔴 Critical |
| Average fill rate | 87.2 % | 🟡 Needs improvement |
| Cancellation rate | 5.8 % | 🟡 Elevated |
| Average lead time | 35.2 days | 🟡 Elevated |
| Stockout events | 794 | 🟡 Elevated |
| Pharmaceutical near-expiry value at risk | $17.2 M | 🔴 Critical |

The on-time delivery rate of **46.9 %** is the headline risk. Fewer than half of all orders arrive on schedule — a structural failure that cascades into every stockout, every emergency expedite, and every near-expiry write-off in this dataset.

---

## Spend by category

| Category | Total Spend | Share of total |
|---|---|---|
| Pharmaceuticals | $27.1 M | 46.5 % |
| Medical Devices | $11.3 M | 19.5 % |
| PPE | $6.6 M | 11.3 % |
| Diagnostic Equipment | $4.8 M | 8.3 % |
| Lab Supplies | $3.3 M | 5.7 % |
| Surgical Supplies | $2.1 M | 3.6 % |
| Orthopedic | $1.5 M | 2.6 % |
| Cleaning & Sanitation | $1.4 M | 2.4 % |

Monthly spend peaked in January 2024 ($3.19 M) and November 2025 ($3.22 M), consistent with recurring flu-season pharmaceutical surges. A gradual mid-year decline is visible across both years.

---

## ABC item analysis — top items by spend

| Item | Category | Spend | ABC Class |
|---|---|---|---|
| Morphine 10 mg/mL | Pharmaceuticals | $8.6 M | **A** |
| Insulin Vials | Pharmaceuticals | $7.8 M | **A** |
| Epinephrine Auto-Injector | Pharmaceuticals | $6.4 M | **A** |
| Saline IV Bags 1 L | Pharmaceuticals | $3.5 M | **A** |
| Blood Collection Tubes | Diagnostic Equipment | $3.5 M | **A** |
| Oxygen Masks | Medical Devices | $3.5 M | **A** |
| IV Catheters 18G | Medical Devices | $3.2 M | **A** |
| Syringes 10 mL | Medical Devices | $2.8 M | **A** |

These 8 items represent over **57 % of total spend**. All are life-critical. Their pharmaceutical average lead time of 41 days and the $17.2 M near-expiry pharmaceutical exposure indicate that existing reorder and rotation practices are insufficient for items of this criticality.

---

## Supplier performance scorecard

| Supplier | Spend | On-time | Fill rate | Lead time | Issue rate | Risk |
|---|---|---|---|---|---|---|
| McKesson Corp | $11.4 M | 64.8 % | 88.4 % | 32.5 d | 22.1 % | 🟢 Low |
| Cardinal Health | $9.9 M | 48.9 % | 88.1 % | 34.8 d | 22.6 % | 🟡 Medium |
| Medline Industries | $9.1 M | 37.4 % | 88.4 % | 36.8 d | 22.3 % | 🟡 Medium |
| Henry Schein | $6.8 M | 54.4 % | 89.0 % | 33.6 d | 21.7 % | 🟢 Low |
| Owens & Minor | $6.1 M | 29.8 % | 87.4 % | 39.1 d | 22.4 % | 🟡 Medium |
| **Local Regional Distributor** | $5.9 M | **14.7 %** | **80.5 %** | 31.9 d | **44.6 %** | 🔴 Critical |
| BD (Becton Dickinson) | $5.8 M | **78.9 %** | **88.8 %** | **30.9 d** | 22.5 % | 🟢 Low |
| **PPE Direct Imports** | $3.2 M | **10.5 %** | **80.6 %** | **53.5 d** | **44.0 %** | 🔴 Critical |

**Issue rate** = combined cancelled + delayed + partial orders as a share of total orders.

**Local Regional Distributor** and **PPE Direct Imports** both deliver on-time less than 15 % of the time, with issue rates exceeding 44 % — double the panel average. PPE Direct Imports carries an average lead time of 53.5 days, 73 % longer than the next slowest supplier. Both suppliers are being used on emergency-priority orders for life-critical items including Morphine and Insulin.

**BD (Becton Dickinson)** is the strongest performer across every metric and should be the preferred partner for dual-sourcing critical items.

---

## Department analysis

| Department | Spend | Stockout events | Stockout rate |
|---|---|---|---|
| Emergency | $9.2 M | **126** | 2.61 % |
| General Ward | $8.2 M | **114** | 2.68 % |
| ICU | $7.6 M | **105** | 2.69 % |
| Surgery | $6.8 M | 83 | 2.35 % |
| Pharmacy | $5.8 M | 102 | **3.40 %** |
| Outpatient Clinic | $4.7 M | 58 | 2.41 % |
| Radiology | $4.4 M | 52 | 2.43 % |
| Laboratory | $4.4 M | 58 | 2.71 % |
| Pediatrics | $4.2 M | 58 | 2.49 % |
| Maternity | $3.0 M | 38 | 2.53 % |

Emergency, ICU, and General Ward collectively account for 44 % of total spend and generate the most stockout events. The Pharmacy department has the highest stockout rate (3.40 %) despite being a managed supply point — reorder thresholds are not calibrated to actual consumption. Lead times are effectively uniform across all departments (~35 days), indicating that expediting processes provide minimal compression even for emergency-priority orders.

---

## Near-expiry inventory risk (≤ 90 days)

| Category | Units at risk | Value at risk |
|---|---|---|
| **Pharmaceuticals** | 113,526 | **$17.2 M** |
| Diagnostic Equipment | 50,260 | $3.7 M |
| Medical Devices | 53,011 | $2.4 M |
| Lab Supplies | 18,430 | $767 K |
| Surgical Supplies | 38,058 | $473 K |
| PPE | 16,144 | $400 K |
| Orthopedic | 6,931 | $332 K |
| Cleaning & Sanitation | 18,489 | $318 K |

The $17.2 M pharmaceutical near-expiry exposure is concentrated in the same Class A items (Morphine, Insulin, Epinephrine, Saline IV Bags) that drive the most spend. This combination of high unit cost, high volume, and high expiry exposure indicates that FEFO (First Expired, First Out) rotation is not being enforced effectively.

---

## Demand forecast

- **Pharmaceuticals** follow a strong seasonal pattern with November–January spikes each year. The November 2025 pharmaceutical spend of $1.98 M was the single largest month in the dataset. This pattern is predictable and should be built into procurement calendars.
- **PPE** spend declined sharply after an early-2024 surge, stabilizing at ~$200 K/month from mid-2024 onward. The 6-month forecast projects a continued gentle decline through mid-2026, suggesting that PPE reorder quantities set during the 2024 surge are now oversized — a likely contributor to near-expiry PPE exposure.

---

## Data quality findings

| Issue | Count | Risk area |
|---|---|---|
| Missing PO numbers | 12 | Audit trail / compliance |
| Duplicate transaction IDs | 50 | Financial reconciliation |
| Quantity received > quantity ordered | 3,530 | Receiving record validation |
| Blank Notes field | ~15,046 (~50 %) | Root-cause analysis |
| Stockout flag not cross-validated | 794 | Threshold logic consistency |

---

## Priority recommendations

1. **Treat on-time delivery as a system-level failure.** Recalibrate reorder-point buffers to reflect actual lead time performance, not planned lead times. Enforce delivery SLAs with financial penalties across all supplier contracts.

2. **Place Local Regional Distributor and PPE Direct Imports on formal performance improvement plans.** For life-critical items currently sourced from these two suppliers (Morphine, Insulin), implement immediate dual-sourcing with BD (Becton Dickinson) or McKesson.

3. **Implement FEFO rotation and weekly cycle counts for Class A pharmaceuticals.** The $17.2 M near-expiry pharmaceutical exposure requires immediate intervention. Morphine, Insulin, Epinephrine, and Saline IV Bags should be placed on weekly inventory review cycles. Consider vendor-managed inventory for the highest-volume items.

4. **Pre-position flu-season pharmaceutical stock by October.** The November–January demand spike is predictable and recurring. The 41-day pharmaceutical average lead time means orders placed in November arrive too late. Advanced procurement by early October is the only way to avoid the crunch.

5. **Right-size PPE reorder quantities.** PPE spend has normalized at roughly one-third of early-2024 surge levels. Current reorder quantities are generating unnecessary holding costs and near-expiry write-offs. A category-level reorder quantity review is recommended.

6. **Remediate data quality gaps.** Mandate structured exception-reason codes for all non-delivered orders. Investigate the 12 missing PO numbers as a compliance risk. Reconcile 50 duplicate transaction IDs before any financial reporting or external audit.

---

## Dataset reference

| Attribute | Detail |
|---|---|
| Analysis period | January 2024 – December 2025 |
| Total transactions | 30,050 |
| Suppliers | 8 |
| Departments | 10 |
| Product categories | 8 |
