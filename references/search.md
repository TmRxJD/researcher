# Search techniques

## Turn questions into searches

Write down the unknown and the type of source that could resolve it. Start with the term the source itself would use. For a failure with several possible causes, search the observed symptom and then each plausible mechanism independently. Include the version if it distinguishes behavior. For sensitive text, use a public error class or sanitized distinctive fragment.

| Intent | Useful first search | Follow-up |
| --- | --- | --- |
| Is a Ghidra API available? | `Ghidra DecompInterface API` | Open versioned docs or source at the deployed tag. |
| Which release fixed a vulnerability? | Exact CVE or advisory ID | Read affected and fixed ranges, then compare them against the lockfile or deployed version. |
| Why does a pipeline drop overrides? | `<product> configuration precedence` | Search the symptom separately. Trace parse, merge, validation, and the runtime consumer. |
| Did a policy change apply this year? | Agency and rule title | Check the official register and effective text for the jurisdiction and date. |
| Does a treatment help? | Intervention and condition | Find recent evidence reviews, then search study databases and registries with a scoped question. |
| What did a circulating image depict? | Caption fragment or original account | Trace earlier appearances and verify time and place independently. |

A neutral query like `<library> connection timeout` can surface causes that `<library> proxy bug` would hide. Once you have a working explanation, search for failed reproductions, contradictory observations, known limits, adverse outcomes, or a newer policy. Search for evidence that could change the answer.

## Choose the index and use its syntax

- **General web.** Use quotes selectively for identifiers, names, errors, or titles. Try unquoted distinctive words when phrasing varies. Use domain, date, language, and file filters where useful. Check operator support. Freshness filters can reflect page updates or index dates. Verify the date at the source.
- **Bibliographic databases.** Build blocks for key concepts. Within each block combine controlled terms, text words, acronyms, and spelling variants with OR. Combine distinct concepts with AND. Use parentheses and platform-specific field tags. Avoid adding an outcome or comparator block unless it improves retrieval because those terms may be absent from titles, abstracts, and indexing.
- **Public records and catalogs.** Search docket numbers, legislation numbers, accession IDs, and other stable identifiers in the relevant registry. Check its effective-date, jurisdiction, version, and status filters. A historical snapshot may answer a different question from the current consolidated text.
- **Code and technical work.** Check versioned docs, tagged source, release notes, issue trackers, and minimal reproductions. When generic guidance conflicts with version-specific material, check behavior for the target version and report that scope. A tracker issue can locate a defect. A released fix or a reproduction at the target version establishes whether it applies.
- **Historical and multilingual work.** Search catalogs, finding aids, editions, original-language names, and transliterations. Distinguish original records from later summaries. Mark translations when wording could affect interpretation.

For a formal search, test whether the strategy retrieves known eligible items spanning different terms or periods. Diagnose misses through indexing, fields, wording, filters, and concepts. Retrieving known items checks for obvious misses and leaves overall recall unknown.

## Repair a weak result set

| What happened | Next move |
| --- | --- |
| Too broad | Add one distinctive term, identifier, source type, or filter. |
| Too narrow | Remove a constraint. Try an alias, original spelling, or another index. |
| Mostly copied summaries | Find the shared original, then search independent reporting, data, or replication. |
| Conflicting dates or versions | Check a change history, archive, or tagged release. Track event, publication, and effective dates separately. |
| Too many recent pages | Search an earlier interval and try historical vocabulary and collections. |
| No full text | Look for an open version, repository, library, or archive. Label abstract-only evidence and record the access gap. |
| Same top hits every time | Change index or source type, then follow references or citations from a strong seed. |

## Follow citations with purpose

Backward searching locates original data, methods, and precedents. Forward searching finds replications, criticism, corrections, and successors. Use multiple seeds when possible. Indexes differ, and selecting only prominent seeds can favor an established account. For reproducible reviews, log seed identifiers, direction, index, date, and screening decisions. Use citation chaining alongside the planned search.

## Further reading

- Strategic exploration and contextual authority. [ACRL Framework for Information Literacy](https://www.ala.org/acrl/standards/ilframework)
- Web search operators and filters. [Google Search Help](https://support.google.com/websearch/answer/2466433)
- Field tags, search translation, and controlled vocabulary. [PubMed User Guide](https://pubmed.ncbi.nlm.nih.gov/help/)
- Search strategy, sources, and study selection. [Cochrane Handbook, chapter 4](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-04)
- Backward and forward citation searching. [TARCiS statement](https://www.bmj.com/content/385/bmj-2023-078384)
