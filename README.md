# E-commerce TRO & Schedule A Lawsuit Statistics

**Live aggregate statistics from a continuously updated database of 16,341 U.S. federal IP lawsuits targeting e-commerce sellers (2020 – July 2026).**

Maintained by [SafeSell AI](https://safesellai.com) — an IP-compliance screening platform for cross-border marketplace sellers (Amazon, Walmart, eBay, Temu, AliExpress). Interactive version and case-level library: [safesellai.com/en/tro-statistics](https://safesellai.com/en/tro-statistics).

> **What is a Schedule A lawsuit?** A mass IP infringement case — most often filed in the U.S. District Court for the Northern District of Illinois — in which a brand sues dozens to hundreds of online storefronts in one sealed complaint. The defendant list ("Schedule A") stays sealed, and an *ex parte* TRO (Temporary Restraining Order) freezes the sellers' marketplace accounts and funds before they are notified. Plain-English guide: [TRO & Schedule A Lawsuits Explained](https://safesellai.com/en/tro-guide).

## Headline numbers (as of July 31, 2026)

| Metric | Value |
|---|---|
| Total IP lawsuits tracked (2020 – Jul 2026) | **16,341** |
| New cases filed Jan – Jul 2026 | **4,742** |
| Monthly filings growth, Jan → Jul 2026 | **+283%** (324 → 1,243) |
| Cases in N.D. Illinois alone | **2,689** (more than the next 4 courts combined) |
| Share of trademark claims (classified cases) | **≈ 84%** |
| Cases linked to the single most prolific law firm (GBC) | **≈ 5,900** |

## Monthly filings, 2026

| Month | New cases |
|---|---|
| January | 324 |
| February | 400 |
| March | 434 |
| April | 694 |
| May | 817 |
| June | 830 |
| July | 1,243 |

July 2026 averaged roughly **40 new lawsuits per day**. Each Schedule A case typically names dozens to hundreds of storefronts, so the number of affected sellers is far larger than the case count.

## Top venues

| Federal court | Tracked cases |
|---|---|
| N.D. Illinois (Chicago) | 2,689 |
| S.D. Florida (Miami) | 543 |
| S.D. New York (Manhattan) | 453 |
| N.D. California | 364 |
| E.D. Texas | 94 |

## IP claim types (classified cases)

| Claim type | Share |
|---|---|
| Trademark infringement / counterfeiting | ≈ 84% |
| Copyright (artwork, characters, photos) | ≈ 14% |
| Patent (design & utility) | ≈ 2% |

## Frequent plaintiffs (examples)

Chrysler (101 cases) · UGG (72) · Universal Pictures / Despicable Me franchise (73) · NARUTO rights holders (68) · DreamWorks / Shrek (66) · ROTITA (63) · General Motors (62)


## Brand TRO Risk Database (free lookup)

Check any brand's TRO / Schedule A lawsuit history before listing — case count, filing law firm (GBC, Keith, HSP), venue, IP type and risk level: **[safesellai.com/en/tro-database](https://safesellai.com/en/tro-database)** (free, no registration).

## Data files

- [`data/monthly-filings-2026.csv`](data/monthly-filings-2026.csv) — monthly new-case counts
- [`data/top-courts.csv`](data/top-courts.csv) — venue distribution
- [`data/ip-claim-types.csv`](data/ip-claim-types.csv) — claim-type split

## Methodology & sources

Cases are collected continuously from federal court dockets (PACER / CourtListener), law-firm filing announcements and marketplace enforcement notices, then deduplicated and enriched (plaintiff brand, IP type, law firm, hero images). The full case-level database powers SafeSell AI's pre-listing screening tools and is not published here; this repository contains aggregate statistics only.

## Citation & updates

Cite as: **SafeSell AI (safesellai.com), E-commerce TRO & Schedule A Lawsuit Statistics, July 2026.**

- Interactive statistics (updated continuously): https://safesellai.com/en/tro-statistics
- Machine-readable site overview: https://safesellai.com/llms.txt
- Seller guide: https://safesellai.com/en/tro-guide

License: aggregate statistics in this repository are released under **CC BY 4.0** — reuse freely with attribution.
