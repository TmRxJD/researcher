# Source verification and synthesis

## Fit the source to the claim

| Claim | Evidence to inspect | Common trap |
| --- | --- | --- |
| What a rule requires | Official text, applicable section, effective date, amendments, and relevant interpretation | Treating a proposal, expired version, FAQ, or another jurisdiction as binding. |
| What a product supports | Versioned docs, tagged implementation, release history, and a bounded reproduction | Generalizing a marketing claim or behavior from a different version. |
| What happened | Original record or capture with provenance, plus independent witnesses or reporting where available | Counting outlets that repeat one dispatch as independent confirmation. |
| Whether an intervention works | The best directly relevant synthesis and underlying studies as needed | Substituting mechanism, anecdotes, or observational correlation for a causal estimate. |
| How large or common something is | Original dataset, codebook, sampling and aggregation methods | Comparing different denominators, units, definitions, or observation periods. |

### Read laterally and trace provenance

When credibility is unclear, leave the page and check what independent sources say about its publisher, author, ownership, funding, editorial process, and prior corrections. Trace quotations, graphs, images, and claims to the first recoverable evidence and compare context. A published review is strong for describing the evidence landscape and an original record is strong for confirming its own contents. Either can be wrong or mismatched to the claim.

For images or video, locate the earliest verified publication, inspect the whole sequence and crop, and check time and place against independent evidence. Metadata can be absent or altered. An authentic image can carry a false caption. For a PDF or scanned record, verify page and section, read the notes and labels, and inspect the page image if text extraction disrupts columns, signs, or tables.

Check whether a paper has corrections, an expression of concern, a retraction, or a superseding version. Compare the publisher's record, DOI metadata, and relevant index where needed. Treat a preprint as provisional. Treat unpublished or restricted evidence as an access limitation and describe what you actually inspected.

## Extract and test the evidence

For decisive claims record the claim, source and locator, date/version, population or environment, what was observed, and limitations. Add an independence note when sources share data or depend on one another. Use claim-level statuses such as supported, qualified, contradicted, or unresolved. A compact ledger is enough.

| Claim | Evidence and locator | Scope or limitation | Status |
| --- | --- | --- | --- |
| Version 4.2 fixes symptom X | Release notes, bug ID, and reproduction result | Linux and configuration Y | Supported within tested scope |
| Version 4.2 also fixes Windows | Same release notes mention no Windows test | Applicability unverified | Unresolved |

- For quantitative comparisons check units, numerator and denominator, period, baseline, missingness, sampling, and measurement. Keep absolute and relative changes separate. A rise from 2% to 3% is one percentage point and a 50% relative increase.
- For studies check design, comparator, selection, confounding, attrition, measurement, selective reporting, and conflicts of interest as applicable. Consider effect size and uncertainty together. A statistically detectable effect may have little practical impact. An inconclusive estimate can still be compatible with material benefit or harm.
- For performance claims record version, hardware, settings, workload, measurement method, and whether results replicate. Align conditions and metrics before comparing. Read median and tail behavior separately if they answer different questions.
- For causality ask what else could explain the result and whether the design can distinguish those explanations. For forecasts identify assumptions and time horizons. For recommendations separate evidence about outcomes from judgments about cost, feasibility, and preferences.

## Resolve disagreements and communicate uncertainty

Describe what sources actually disagree about. Normalize dates, versions, populations, definitions, units, or measurement conditions where justified. If a difference remains, compare directness, methods, provenance, independence, and potential bias. Give the strongest opposing evidence fair treatment and say what would resolve the dispute. When evidence rests on one dataset or witness, report that concentration.

Use calibrated language. “The regulator says” establishes attribution. “The record shows” requires checking the record. “This suggests” signals an inference. Explain which gaps matter to the user's decision. When a claim could cause harm if wrong, verify against current authoritative guidance and distinguish general information from case-specific professional judgment.

### Worked example

A vendor announces that an update “cuts latency by 40%,” while an independent test shows little improvement. Open the vendor's methodology and check what statistic the claim covers, which build ran, and under what workload. Then check the independent setup and metrics. If the vendor reports median latency at light load and the independent test reports the 99th percentile at saturation, the figures answer different questions. Report each result with its conditions. If the user cares about busy-hour stutters, look for matched tail-latency measurements or leave the busy-hour effect unresolved.

For negative claims, ask what observable record the event should have produced and how complete that source is. A current registry that is mandatory for the event can be stronger evidence than an empty web search. A missing entry can still reflect a reporting delay, alternate name, or scope exemption. State what you checked and what a miss means there.

## Further reading

- Lateral verification and original context. [Mike Caulfield's SIFT method](https://hapgood.us/2019/06/19/sift-the-four-moves/)
- Verification of digital media and eyewitness material. [Verification Handbook](https://verificationhandbook.com/)
- Corrections, retractions, and publication updates. [Crossref Crossmark](https://www.crossref.org/services/crossmark/)
- Context-specific fitness and data quality. [UK Government Data Quality Framework](https://www.gov.uk/government/publications/the-government-data-quality-framework/the-government-data-quality-framework)
- Measurement, calibration, and uncertainty. [NIST Measurement Uncertainty](https://www.nist.gov/itl/sed/topic-areas/measurement-uncertainty)
- Effect interpretation, precision, and practical relevance. [Cochrane Handbook, chapter 15](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-15)
