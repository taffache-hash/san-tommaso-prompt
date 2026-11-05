# SAN TOMMASO — Integrated Master Prompt (v0.6)

**Author:** Paolo Taffache  
**Affiliation:** General and Pediatric Anesthesia and Intensive Care Unit, IRCCS Azienda Ospedaliero-Universitaria di Bologna  
**Status:** Conceptual/experimental resource; **not empirically validated**.  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0; see `LICENSE`).

## What this repository contains

This repository distributes the **single canonical SAN TOMMASO master prompt**, in a plain-text format ready to copy. It is intended to coordinate a source-traceable, human-governed draft audit of a scientific manuscript and associated research documents across 17 domains (`D01`–`D17`). It combines prospective scoping, evidence-to-claim checks, document/version reconciliation, four linked evidence-ledger tables, issue tracking and human adjudication instructions.

It is **one integrated prompt**, not a collection of independently validated checklists or an automated certification service. Its output is a **draft audit**. The prompt cannot guarantee access to full texts, correct conclusions, reproducible model behavior or independent verification. A qualified human remains responsible for checking evidence and approving findings.

This repository deliberately **does not contain the journal manuscript or manuscript supplements**.

## How to use the prompt

1. Open [`SAN_TOMMASO_Master_Prompt_v0.6.txt`](SAN_TOMMASO_Master_Prompt_v0.6.txt) and copy its **entire contents** into a compatible language-model session.
2. Supply the manuscript and related materials that you are **authorized** to disclose. Confirm privacy, copyright and platform/institutional requirements before uploading full texts or confidential data.
3. The prompt first requests a **prospective scope/inventory**. Review the proposed audit scope; it is a plan, **not evidence of completed checking**.
4. Work through the selected checks. The model should record precisely which sources and passages it actually inspected, and which remain missing or unverified.
5. Review the claim-source ledger, findings, uncertainties and proposed corrections **yourself**. Retain the human decision record and any separately authorized manuscript revisions.

The prompt is designed for interactive use and staged outputs when the audit exceeds session or context limits. One copy-and-paste action does **not** imply that all checks will finish without further documents, exchanges or human decisions.

## Versions and provenance

- **Canonical prompt:** v0.6, dated 4 November 2026.
- **Related manuscript:** v0.7/v0.7.1 at the time this repository was prepared; the different manuscript version does **not** imply a change to this prompt.
- **Original prompt SHA-256:** `6cb1a0b9520b4ccb9fe1314e9042566301f2f09590d7f16e538b3f1cc68c0d51`.
- This repository package preserves the verified v0.6 prompt bytes unchanged; only publication metadata and explanatory files have been refined.

## Citation and DOI

The repository includes `CITATION.cff` so GitHub and Zenodo can identify the title, version, author, affiliation and license. **No Zenodo DOI has yet been assigned.** After the `v0.6` GitHub release is archived via Zenodo, cite the DOI of the specific archived version. Please do not substitute the DOI of a journal paper for the DOI of the prompt.

## Reuse and responsibility

You may copy, adapt and redistribute the original material under **CC BY 4.0**, with appropriate attribution and indication of changes. This license does not grant rights to third-party papers or other content that users may provide to an AI model. Use of this experimental resource is at the user's scientific and ethical discretion, and human review is required for consequential claims.