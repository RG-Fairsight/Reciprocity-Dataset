# The Reciprocity Dataset

**An open, hand-coded dataset testing a quiet asymmetry in life-sciences job descriptions: at the same organizational level, are non-commercial roles required to be fluent in the business while commercial roles are *not* required to be fluent in compliance?**

---

## The question

Compliance, legal, quality, and medical professionals are routinely expected to be "business-minded" — to read a P&L, to understand gross-to-net, to speak the commercial language as a condition of being taken seriously. This dataset asks whether the reverse expectation exists in equal measure: are commercial, operational, and finance leaders asked to learn the compliance/regulatory language with the same seriousness?

It is a question about **reciprocal cross-domain fluency** — and, so far, the answer in the sample is that the expectation runs in one direction.

## What this is (and isn't)

This is a **pilot content analysis**, not a representative labour-market study. It began as a single practitioner's observation and is being opened up so others can test, extend, or break it. Treat the current numbers as illustrative. The value of the project is the open method, not the size of the sample — yet.

## Current snapshot

| | Compliance | Commercial |
|---|---|---|
| Postings coded (n) | 10 | 8 |
| of which read in full text | 5 | 5 |
| Requires the *other* domain's fluency **as a qualification** — YES | 6 | 0 |
| — PARTIAL | 4 | 0 |
| — NO | 0 | 8 |

In the sample, every compliance posting expected business/finance fluency as a candidate qualification; no commercial posting required compliance fluency as a qualification. Where compliance appeared in commercial postings, it appeared as a *responsibility to discharge* ("ensure adherence to FDA/OIG," "partner with Legal/Compliance"), never as knowledge the candidate had to possess.

## Files

- `jd_reciprocity_dataset.csv` — the coded dataset
- `JD_reciprocity_analysis.xlsx` — same data with methodology & limitations tabs

## Data dictionary

| Column | Meaning |
|---|---|
| `bucket` | Compliance (non-commercial) or Commercial |
| `reciprocal_fluency_required_as_qualification` | YES / PARTIAL / NO — the crux variable |
| `how_other_domain_appears` | Qualification vs. delegated responsibility vs. absent |
| `verification` | Full-text fetched or Excerpt verified |
| `source_url` | Link to the posting |

*See the full data dictionary and methodology* at the end of this document.

## The decisive coding rule

A posting that says "ensure adherence to FDA/OIG" or "partner with Legal/Compliance" codes **NO**. Accountability for an outcome ≠ fluency in the subject. Only knowledge the candidate must *bring* counts as a qualification.

## Limitations

- Pilot/convenience sample, not representative.
- n=18 (10 compliance, 8 commercial).
- Director/Associate Director level (C-suite is privately recruited, not posted).
- Two rows are health-tech, not core pharma.
- JD language ≠ actual behavior.
- Postings expire; links may not be live.

## How to contribute

**Submit a job description → [Airtable](https://airtable.com/appYwQWIEYoQiYes2/paguChgYUENzDCDYr/form)**

Any role, any function, any level. You submit the link; I code it. The form has all the instructions.

## Citation

> *The Reciprocity Dataset.* Version 1, May 30 2026. Available at https://github.com/RG-Fairsight/Reciprocity-Dataset/blob/main/jd_reciprocity_dataset.csv

# Methodology & Limitations

## Research question

At the same organizational level, is there an asymmetry in reciprocal cross-domain fluency expectations between non-commercial (compliance) and commercial/operational job descriptions?

## Sample
Hand-coded convenience (non-random) sample of US pharma / biotech / life-sciences postings sourced from stable job-board domains (Greenhouse, BuiltIn) and read directly. Level held to Manager / Associate Director / Director / (a few Executive Director / VP) — i.e. the levels that ARE posted publicly. 

**n = 18 total** (10 compliance, 8 commercial); 5 per bucket were fetched and read in FULL, the remainder coded from genuine posting excerpts with the source URL recorded.

## Why not C-suite (COO/CFO/CCO)?

Confirmed during data collection: senior commercial/operational C-suite roles (COO, CFO, CCO) are almost never posted publicly with full descriptions — they are recruited privately. That scarcity is itself a finding, but it meant a clean C-level comparison was not available. Dropping to Director/AD level — where both functions *are* posted with real requirements — is what makes a like-for-like, verifiable comparison possible.

## Coding rubric

Each posting was coded for:

1. **Degree expectation** as written
2. **Advanced degree** (MBA/JD) required vs. preferred vs. not mentioned
3. **The crux variable** — does the posting require the *other* domain's fluency as a candidate qualification? (YES / PARTIAL / NO)
4. **How the other domain appears** — qualification vs. delegated responsibility vs. absent
5. **Compliance/regulatory concepts named** in the posting
6. **Business/finance concepts named** in the posting

## The key coding distinction: qualification vs. responsibility

A commercial posting that says **"ensure adherence to FDA/OIG"** or **"partner with Legal/Compliance"** is coded **NO** — the candidate is accountable for compliance *outcomes* but is not required to *possess* compliance fluency. 

This distinction is the heart of the analysis and is applied consistently across every row: **only knowledge the candidate must *bring* counts as a qualification.**

## Verification status & posting volatility

- **Full-text fetched** = the complete posting body was retrieved and read in full.
- **Excerpt verified** = a genuine excerpt (including relevant requirements language) was retrieved with URL recorded; full body not separately fetched.

Job postings expire fast: several originally-indexed postings had already been removed by the time of final coding. One row (Vertex) is an archived posting whose text was preserved. For "Excerpt verified" commercial rows, **NO** means "no compliance concept in the reviewed text," not a guaranteed full-document absence.

## Known limitations (state these if published)

- **It is a pilot, not a census.** n = 18 is an illustration, not a market-wide statistic, and should never be dressed up as one.
- **Convenience sample.** It skews toward companies that post on public boards, which skews smaller and toward biotech.
- **Levels are not perfectly matched** on every row; a few ED/VP rows are included where Director-level was unavailable.
- **The C-suite is largely missing** — the level where the asymmetry probably matters most — precisely because those roles are not posted.
- **Two rows are health-tech**, not core pharma, and are flagged as such.
- **JD language is not behavior.** A posting reflects what an employer chooses to *write*, which may differ from what it expects or tests in the room.
- **Postings expire.** Several rows are archived/preserved; verify live links before relying on them.

## Appropriate framing for publication

Present as: **"In a hand-coded sample of 18 pharma/life-sciences postings at Director/AD level..."** — never as a definitive market-wide statistic. 

Pair with published board-training benchmarks (IBE 2021 n=125; Skillcast; NAVEX 2025) which ARE survey-grade for the quantitative backbone.

## Board-training benchmarks (survey-grade, citable)

- **IBE 2021** (n=125 E&C practitioners): 51% of organizations provide ethics and compliance training to their boards.
- **Skillcast annual survey**: ~40% of boards regularly participate in training vs. ~70% of senior managers actively engaged in compliance.
- **NAVEX 2025**: Only 64% of boards receive periodic reports on compliance matters; only 52% have formal oversight of the compliance program.

(Verify each at source before quoting.)

## Contributor submission and coding

New submissions are coded by the maintainer using the same rubric to ensure consistency as the dataset grows. The decisive coding rule (qualification vs. delegated responsibility) is applied uniformly.

Contributors submit links to public postings only (not full JD text) to keep the dataset copyright-clean and focused on the analytic coding rather than reproduction.

## Dataset versioning and citation

The dataset is versioned by scan date (e.g. v1.0 / 2026-05-30). Each release includes the CSV and the full Excel workbook with all tabs.

Suggested citation format:
> *The Reciprocity Dataset.* Version [x], [date]. Available at [repository URL].

For a citable, timestamped, DOI-minted snapshot, periodic releases can be mirrored to an archive (e.g. Zenodo or OSF).

---

*A Values-Driven Compliance project. Contributions, corrections, and disconfirming evidence welcome.*


