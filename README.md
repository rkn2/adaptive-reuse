# Centre County Adaptive Reuse Inventory

A merged inventory of historically significant, underutilized, and vacant properties in
Centre County, PA, with field-verified condition assessments contributed by undergraduate
researchers in the Napolitano lab (Penn State Civil & Environmental Engineering).

## What's here

- `data/raw/` -- GIS feature service exports (JSON) from Centre County and state sources
- `data/processed/` -- cleaned CSVs ready for analysis and cross-referencing
- `field-forms/` -- condition assessment templates for site visits
- `docs/` -- data source documentation and project notes

## Data sources

| Dataset | Records | Source | Last pulled |
|---|---|---|---|
| Bellefonte Historic Sites survey | 442 | Centre County GIS (BellefonteHistoricSites/MapServer) | 2026-09-19 |
| National Register of Historic Places | 64 | Wikipedia / NPS NRHP | 2026-09-19 |
| PA-SHARE historic resources | 9,181 | PA SHPO SearchLite API (share.phmc.pa.gov) | 2026-09-19 |
| County underutilized buildings | 8 | Centre County GIS (Underutilized_Vacant/MapServer) | 2026-09-19 |
| County vacant lands | 54 | Centre County GIS (Underutilized_Vacant/MapServer) | 2026-09-19 |

## Stakeholders

- Centre County Economic Development -- interested in office-to-affordable-housing conversions
- Centre County Historical Society (info@centrecountyhistory.org) -- outreach sent 2026-09-18
- Penn State OPP -- outreach sent re: campus building condition assessment

## Student contributions

Students (5-10 hrs/week) can:
1. Cross-reference and merge records across datasets (match by tax ID, address, location)
2. Field-verify condition for properties in the inventory (use forms in `field-forms/`)
3. Photo-document buildings and add standardized condition ratings
4. Flag properties with adaptive reuse potential, especially office-to-residential candidates
5. Research zoning, ownership, and recent sale history for flagged properties
