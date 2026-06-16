# Dr. Turner Media Tracker - v7 Decision Log

**Date:** April 8, 2026  
**Prepared by:** J. Turner Strategic Consulting  
**Baseline:** DrTurnerMediaTracker_v6.jsx (178 entries, ids 1-178)  
**Output:** DrTurnerMediaTracker_v7.jsx (204 entries, ids 1-204)

---

## Summary of Changes

| Category | Count | Description |
|----------|-------|-------------|
| A. LF999 Summary Correction | 1 | id:36 updated with verified stats from LF999 Final Airings Report |
| B. New LF999 TV Station Entries | 17 | ids 179-195, individual station entries from LF999 report |
| C. New LF999 Online Entries | 2 | ids 196-197, online syndication entries with verified URLs |
| D. New Forbes Health Entry | 1 | id:198, Tier 1 article placement |
| E. New LF999 Radio Entries | 6 | ids 199-204, radio station entries from LF999 report |
| F. Hero Stats Reordered | 1 | Descending order, Peak Event Reach now leads |
| G. Peak Event Reach Display | 1 | Full number "12,397,409+" replaces "12.1M+" |
| H. useCountUp Fix | 1 | Comma-formatted numbers now animate correctly |
| I. Em-Dash/En-Dash Purge | 195 | All dashes replaced with hyphens |
| J. CITY_COORDS Additions | 13 | New city coordinates for LF999 markets |
| K. Footer/Version Updates | 3 | v7, date, data source attribution |
| **TOTAL** | **241 individual changes** | |

---

## A. LF999 Summary Correction (id:36)

| Field | Old Value (v6) | New Value (v7) | Source |
|-------|----------------|----------------|--------|
| Title | "...43 Outlets, 12.1M Impressions" | "...49 Outlets, 366 Hits, 12.4M Impressions" | LF999 Final Airings Report, March 21, 2024 |
| Description stats | "43 outlets, 12.1M impressions" | "49 outlets, 366 hits, 12,397,409 total impressions" | LF999 Final Airings Report, March 21, 2024 |
| Tier | Tier 1 | Tier 1+ | Upgraded per scope/impact |

**Note:** id:69 (Carmela Wallace press release) still references old stats "43 outlets, 12.1M impressions" - flagged for future consistency update.

---

## B. New LF999 TV Station Entries (ids 179-195)

All entries sourced from LF999 Final Airings Report, March 21, 2024. Duplicate station airings combined into single entries per-station.

| ID | Station | Affiliate | Market | Airings | Impressions | Date | URL Status |
|----|---------|-----------|--------|---------|-------------|------|------------|
| 179 | KDVR-TV | FOX | Denver, CO (#16) | 1 | 68,210 | 2024-02-27 | Needed |
| 180 | WKCF-TV | CW | Orlando, FL (#17) | 1 | 25,800 | 2024-02-27 | Needed |
| 181 | KTXL-TV | FOX | Sacramento, CA (#20) | 1 | 60,320 | 2024-02-27 | Needed |
| 182 | KPLR-TV | CW | St. Louis, MO (#24) | 1 | 43,959 | 2024-02-27 | Needed |
| 183 | KTVI-TV | FOX | St. Louis, MO (#24) | 1 | 56,959 | 2024-02-27 | Needed |
| 184 | WBNS-TV | CBS | Columbus, OH (#32-33) | 2 | 89,892 | 2024-03-19 | Needed |
| 185 | KTBC-TV | FOX | Austin, TX (#35) | 1 | 43,509 | 2024-02-28 | Needed |
| 186 | WXIX-TV | FOX | Cincinnati, OH (#36) | 2 | 94,572 | 2024-02-27 | Needed |
| 187 | KTNV-TV | ABC | Las Vegas, NV (#40) | 1 | 27,005 | 2024-02-28 | URL verified live (ktnv.com) |
| 188 | WAVY-TV | NBC | Norfolk, VA (#44) | 1 | 55,831 | 2024-02-29 | Needed |
| 189 | WHAS-TV | ABC | Louisville, KY (#48) | 1 | 58,122 | 2024-03-05 | Dead URL (403 - whas11.com) |
| 190 | WMC-TV | NBC | Memphis, TN (#50) | 2 | 37,690 | 2024-02-27 | URL verified live (actionnews5.com) |
| 191 | WRGB-TV | CBS | Albany, NY (#60) | 2 | 59,374 | 2024-03-18 | Needed |
| 192 | WSET-TV | ABC | Roanoke, VA (#71) | 1 | 21,011 | 2024-03-01 | Needed |
| 193 | WHNT-TV | CBS | Huntsville, AL (#81) | 1 | 26,865 | 2024-03-16 | URL verified (Google Drive mp4) |
| 194 | WRCB-TV | NBC | Chattanooga, TN (#84) | 1 | 25,300 | 2024-02-01 | Needed |
| 195 | WBBJ-TV | ABC | Jackson, TN (#175) | 1 | 42,856 | 2024-02-27 | Needed |

**Combination notes:**
- WBNS Columbus (id:184): 2 airings combined (6:00 AM + 12:00 PM, same day)
- WXIX Cincinnati (id:186): 2 airings combined (8:00 AM + 6:00 PM, same day)
- WRGB Albany (id:191): 2 airings combined (5:00 AM + 6:00 AM, same day)
- WMC Memphis (id:190): 2 airings combined (dates differ: 2024-02-27 and 2025-03-05 per report)

---

## C. New LF999 Online Entries (ids 196-197)

| ID | Station | Market | Impressions | Date | URL Status |
|----|---------|--------|-------------|------|------------|
| 196 | WCTV-TV Online | Tallahassee, FL | 308,000 | 2024-02-27 | URL verified live (wctv.tv) |
| 197 | WIBW-TV Online | Topeka, KS | 784,000 | 2024-02-27 | URL verified live (wibw.com) |

Type set to "Article" (online syndication).

---

## D. New Forbes Health Entry (id:198)

| ID | Title | Outlet | Tier | Date | URL Status |
|----|-------|--------|------|------|------------|
| 198 | Forbes Health - Suicide Prevention: Risk Factors, Protective Strategies And Misconceptions | Forbes Health | Tier 1 | 2025-09-23 | URL verified (Jimmie-confirmed) |

---

## E. New LF999 Radio Entries (ids 199-204)

All entries sourced from LF999 Final Airings Report, March 21, 2024. Type set to "Radio" (new category in v7).

| ID | Station | Market | Rank | Airings | Impressions | Date | Program |
|----|---------|--------|------|---------|-------------|------|---------|
| 199 | Good News Radio | National | -- | 311 | 1,231,272 | 2024-02-27 | The Angie Austin Show |
| 200 | WKNY-AM | New York, NY | #1 | 1 | 96,745 | 2024-02-27 | News |
| 201 | KKVI-FM | Dallas, TX | #5 | 1 | 120,000 | 2024-02-27 | Real Talk Radio |
| 202 | KORE-FM | Seattle, WA | #13 | 1 | 38,454 | 2024-03-04 | News |
| 203 | WFSK-FM | Nashville, TN | #26 | 1 | 38,695 | 2024-03-11 | News |
| 204 | WNNK-AM (4 Sister Stations) | Harrisburg, PA | #42 | 5 | 57,600 | 2024-03-03 | News |

**Tier assignments:**
- id:199 (Good News Radio): Tier 1 - national syndication, 311 airings, 1.2M+ impressions
- ids 200-204: Tier 2 - regional market radio placements

---

## F. Hero Stats Reordered (Descending)

New order:
1. 12,397,409+ Peak Event Reach
2. Catalogued Entries (computed)
3. Unique Outlets (computed)
4. Tier 1 Placements (computed)
5. Cities Reached (computed)
6. 20 Years Experience

---

## G. Peak Event Reach Display

Changed from "12.1M+" to "12,397,409+" (full number with commas).

---

## H. useCountUp Fix

Added `hasCommas` detection in the `useCountUp` animation function. Numbers containing commas now animate with `toLocaleString()` formatting. The "+" suffix is preserved separately from comma handling.

---

## I. Em-Dash/En-Dash Purge

v6 project file contained 192 em-dashes and 3 en-dashes despite prior purge note. All 195 replaced with hyphens in v7. Verified zero remaining.

---

## J. CITY_COORDS Additions

| City | Lat | Lng | Reason |
|------|-----|-----|--------|
| Denver, CO | 39.74 | -104.99 | LF999 TV market |
| Orlando, FL | 28.54 | -81.38 | LF999 TV market |
| St. Louis, MO | 38.63 | -90.20 | LF999 TV market (both spellings) |
| St Louis, MO | 38.63 | -90.20 | LF999 TV market (no period variant) |
| Norfolk, VA | 36.85 | -76.29 | LF999 TV market |
| Albany, NY | 42.65 | -73.76 | LF999 TV market |
| Roanoke, VA | 37.27 | -79.94 | LF999 TV market |
| Huntsville, AL | 34.73 | -86.59 | LF999 TV market |
| Chattanooga, TN | 35.05 | -85.31 | LF999 TV market |
| Jackson, TN | 35.61 | -88.81 | LF999 TV market |
| Memphis, TN | 35.15 | -90.05 | LF999 TV market |
| Topeka, KS | 39.05 | -95.68 | LF999 online market |
| Dallas, TX | 32.78 | -96.80 | LF999 radio market |
| Harrisburg, PA | 40.27 | -76.88 | LF999 radio market |

Note: Dallas includes both "dallas, tx" and "dallas,tx" (no space variant from LF999 report).

---

## K. Footer/Version Updates

| Element | Old (v6) | New (v7) |
|---------|----------|----------|
| Version string | v6 | v7 |
| Updated date | April 3, 2026 | April 8, 2026 |
| Data sources | "Google Drive + Web Research" | "Google Drive + Web Research + LF999 Final Airings Report" |
| Total estimated | 210+ | 216+ |

---

## URL Verification Log

| URL Target | Status | Used On |
|------------|--------|---------|
| actionnews5.com (WMC Memphis) | LIVE | id:190 |
| Google Drive mp4 (WHNT Huntsville) | ACCESSIBLE | id:193 |
| ktnv.com (KTNV Las Vegas) | LIVE | id:187 |
| whas11.com (WHAS Louisville) | DEAD (403) | id:189 gets url:"" |
| wctv.tv (WCTV Tallahassee) | LIVE | id:196 |
| wibw.com (WIBW Topeka) | LIVE | id:197 |
| forbes.com/health (Forbes Health) | Blocked by fetcher, Jimmie-verified | id:198 |

---

## Deliverables Produced

1. `DrTurnerMediaTracker_v7.jsx` - 204 entries, ids 1-204
2. `DrTurnerMediaTracker_v7.html` - Standalone HTML build
3. `DrTurner_MediaTracker_URLs_Needed_v3.xlsx` - 113 entries (93 from v2 + 20 new)
4. `DrTurner_v7_DecisionLog.md` - This document

---

## Open Items

1. **id:69 consistency** - Carmela Wallace press release still references old stats "43 outlets, 12.1M impressions" - not in scope for v7 but flagged for future update
2. **113 URLs still needed** - See URLs_Needed_v3.xlsx
3. **LF999 online entries not yet added** - The LF999 report lists 26 online syndication entries beyond the 2 added (ids 196-197). These could be added in a future version if desired.
