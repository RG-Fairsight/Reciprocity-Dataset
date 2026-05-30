# Reciprocity-Dataset
An open, hand-coded dataset testing a quiet asymmetry in life-sciences job descriptions: at the same organizational level, are non-commercial roles required to be fluent in the business while commercial roles are not required to be fluent in compliance?

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

(Full data dictionary in the spreadsheet's Methodology tab.)

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

**[Submit a job description →][Airtable](<iframe class="airtable-embed" src="https://airtable.com/embed/appYwQWIEYoQiYes2/paguChgYUENzDCDYr/form" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>)**

Any role, any function, any level. You submit the link; I code it. The form has all the instructions.

## Citation

> *The Reciprocity Dataset.* Version [x], [date]. Available at [GitHub repo URL].

---

*A Values-Driven Compliance project. Contributions, corrections, and disconfirming evidence welcome.*


