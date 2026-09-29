# Connected Research Library Retrieval Protocol

## 1. Start with the exegetical question

Retrieval begins only after the SDS has identified a material question or specialised claim.

Examples:

- What is the discourse force of a conjunction?
- Which referent best explains a pronoun?
- What historical practice is presupposed?
- What are the principal live readings of a disputed expression?
- Does a proposed theological conclusion depend on a contested syntactic relation?

Do not begin with "search everything about this passage".

## 2. Route by SDS research mode

### TEXT_BOUND

Do not query the connected library unless the user explicitly reopens the research mode.

### STANDARD_VERIFIED

Query the connected library when a material specialised, disputed, or high-consequence claim needs verification.

### DEEP_EXEGETICAL_RESEARCH

Search broadly enough to surface competent alternatives, source dependence, and significant counter-evidence.

## 3. Search order

1. Search the structured library index by passage, topic, issue, author, and source competence.
2. Retrieve relevant source cards.
3. For material claims, inspect the original source location when needed to verify attribution or context.
4. If the structured library is insufficient, search the connected Drive source archive.
5. Inspect only the relevant source sections before expanding.
6. Create or update source cards for genuinely reusable findings.
7. Create or update an issue dossier when multiple live interpretations matter.
8. Populate the SDS `EXEGETICAL_SOURCE_LEDGER`.
9. Adjudicate for the current project.

## 4. Claim extraction

A reusable extracted claim should contain:

- a stable `claim_id`;
- passage/topic/issue;
- paraphrased contribution;
- exact source location;
- contribution type;
- source competence;
- independence group;
- contested status where relevant;
- confidence;
- optional short quotation only when wording itself matters.

Do not store an interpretation without enough location data to recover its context.

## 5. Independence audit

Several secondary sources do not count as independent corroboration merely because they are different books.

Where one source explicitly follows or materially reproduces another argument:

- give them the same `independence_group`; or
- record the dependence in the source card.

## 6. Preserve disagreement

When a question remains live, create an issue dossier.

A dossier should distinguish:

- position summary;
- principal evidence;
- principal objections;
- competent sources;
- dependence groups;
- unresolved questions.

Do not rewrite the dossier into a single consensus statement merely because one project adopts a view.

## 7. Project adjudication

A project adjudication may say which position governs the sermon and why.

It is not automatically promoted into the source library as established fact.

The adjudication should preserve:

- governing judgment;
- confidence;
- supporting claim IDs;
- live alternatives;
- downstream sermon constraints.

## 8. Source-access discipline

`CONNECTED_LIBRARY` means the connected resource or its verified structured derivative was actually consulted.

Do not name a source as current-project provenance from model memory alone.

If a source card is too compressed to verify the material point, reopen the original source.

## 9. Search stopping rule

Stop when the evidence is adequate for the claim's consequence level.

Do not accumulate citations after the material interpretive uncertainty has been resolved sufficiently for the project.

## 10. Library growth rule

The library should grow **just in time**.

A sermon project should leave behind structured reusable evidence only where that evidence is likely to matter again.

The aim is cumulative research memory, not maximal ingestion.
