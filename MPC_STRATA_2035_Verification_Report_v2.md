# MPC STRATA 2035 — Database Verification Report v2

**Created:** 11 November 2026  
**Source workbook:** MPC_STRATA_2035_Complete_Database.xlsx  
**Output workbook:** MPC_STRATA_2035_Verified_Comprehensive_v2.xlsx  
**Sheets:** 105  
**Data dictionary entries:** 998  
**Automated checks:** 411 (410 PASS, 1 flagged)

## Scope and limitations

The 3 pillars / 15 agenda action titles come from the **interim** MPB 2035 report, pp.245–246, not a final endorsed taxonomy. MPC public organisation details are reference-only. Directorate owner assignments, KPIs, evidence and workflow states of six examples remain demonstrative. No official corporate annual workplans or KPI scorecards were provided.

## Corrected defects

- Removed external implementation partner from MPC organisational tree (legacy ORG-008 → EXT-001), updating its RACI reference.
- Marked old fictional placeholder units as legacy demo-only, and added publicly documented functional sections and 2025 manual regional offices without claiming formal reporting lines.
- Added an extensive schema for source lineage, stocktake, RACI authority, KPI methodologies, protected evidence, impact evaluation, AI governance and security.
- Extended data dictionary to include foreign-key target, source category, sensitivity, validation rules and owner.

## Remaining evidence gaps

Official 2026 MPC chart; approved 2026–2027 division workplans; signed division scorecards; final MPB 2035 framework; official programme evidence and actuals; decision delegations; records/data-classification policies. See **97_DATA_REQUESTS** tab.

## Automated integrity checks

| Test | Result | Count | Detail |
|---|---|---:|---|
| Demo RACI proposals with Accountable role still unassigned | CHECK | 1 | Expected unresolved owner in DEMO-005; must be confirmed by MPC, do not invent |

## Sources

- Laporan Interim - Kajian Kerangka dan Pelan Hala Tuju Produktiviti Nasional (1).pdf, pp.245-246
- MANUAL KUALITI DAN ANTI RASUAH MPC edited 031025.pdf, pp.9-10 (6 Jun 2025)
- https://www.mpc.gov.my/management-mpc
- https://www.mpc.gov.my/Background-And-Rationale
