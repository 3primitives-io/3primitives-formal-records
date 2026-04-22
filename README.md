# Three Primitives — Formal Records Archive

## Why This Repository Exists

On **February 26, 2026**, Zenodo's automated spam filter suspended the account associated with `pyrateruby@gmail.com` and removed **nine formal research records** with their associated DOIs. These records form the mathematical corpus of the Three Primitives AI governance framework.

The records were deposited in good faith between **December 2025 and February 2026**. They are not spam. They are original, peer-structured formal mathematical proofs.

We have been trying to get them restored for **six weeks**. We have contacted Zenodo support from two separate accounts, posted to the CERN GitHub, posted to the CERN OQI community (where co-author Pyrate Ruby Passell is a known member), and escalated to the CERN Service Desk. 

## As of April 20, 2026, Zenodo support has reinstated the account and confirmed restoration of the nine affected records. However, the records are not currently linked to the account dashboard and remain accessible only via direct URLs. The restoration is therefore incomplete.

**This repository exists to preserve public access to the original formal records with their original PDF metadata intact, while the Zenodo restoration remains unresolved.**

The PDF creation dates embedded in each file's metadata reflect the original authoring dates. These dates are verifiable by anyone and do not change when files are uploaded to a new location.

## The Work

Three Primitives is a formal mathematical framework proving that **AI cannot govern AI**. The core result: the mapping from detection to action in any automated decision-making system is non-unique, which means no system can legitimately select an action without an explicit human authority declaration. This is a structural proof, not a policy argument.

The framework was discovered by **Pyrate Ruby Passell** (Lead Developer) and **Stacy Gildenston** (Lead Architect), operating through [3primitives.io](https://3primitives.io).

The work has been circulated through the UN, CERN OQI, and multiple related experts.

## Original Zenodo Deposits (Provenance Archive)

The `/zenodo-originals/` folder contains the nine formal records exactly as they were deposited on Zenodo between December 2025 and February 2026. **These files have not been modified.** Their PDF metadata contains the original creation dates, which serve as the evidentiary record of discovery.

Do not update or replace these files. Their value is the preserved timestamps.

### Foundation

| Record | Title |
|--------|-------|
| FR1 | Three Primitives — Canonical Logic Sequence |
| FR2 | AI Cannot Govern AI: A Formal Proof of Structural Openness in Intelligent Systems |
| FR3 | ADCI Closure Theorem (Value Layer): Agency, Dignity, Continuity, Interpretive Authority |

### Structural Lemmas

| Record | Title |
|--------|-------|
| FR4 | The Adjacency Lemma: The Interface-Authority Boundary |
| FR5 | Lemma C — Ghost Authority Lemma |

### Closure Results

| Record | Title |
|--------|-------|
| FR6 | The Law of Declared Authority: Necessary Closure for Legitimacy in Decision-Permitting Systems |
| FR7 | Bell Non-Closure and the Law of Declared Authority: A Structural Correspondence |
| FR8 | Twisted Pair Legitimacy Theorem (Dual-Legitimacy Architecture) |

### Derived

| Record | Title |
|--------|-------|
| FR9 | AGI as a Decision-Complete System: A Mathematical Definition |

## PDF Metadata Dates (Provenance Verification)

All dates below are embedded in the PDF file metadata and can be independently verified using `pdfinfo`, `exiftool`, or any PDF metadata viewer. These dates do not change when files are copied, downloaded, or uploaded.

| Record | Title | PDF Creation Date | Notes |
|--------|-------|------------------|-------|
| FR1 | Canonical Logic Sequence | December 28, 2025 | ✅ Verified |
| FR2 | AI Cannot Govern AI | January 10, 2026 | ✅ Verified |
| FR3 | ADCI Closure Theorem | February 12, 2026 | ✅ Verified |
| FR4 | Adjacency Lemma | January 10, 2026 | ✅ Verified |
| FR5 | Ghost Authority Lemma | January 16, 2026 | ✅ Verified |
| FR6 | Law of Declared Authority | January 18, 2026 | ✅ Verified |
| FR7 | Bell Non-Closure | February 25, 2026 | ✅ Verified |
| FR8 | Twisted Pair Legitimacy Theorem | February 12, 2026 | ✅ Verified |
| FR9 | AGI as Decision-Complete System | January 8, 2026 | ✅ Verified |

## How to Verify Dates

To verify the original creation dates of these files, download any PDF and check its metadata:

- **Windows:** Right-click > Properties > Details > look for "Date created" under the PDF metadata section (not the file system date)
- **Mac:** Use Preview > Tools > Show Inspector > look for "Created"
- **Command line:** Run `exiftool filename.pdf` or `pdfinfo filename.pdf` to see full metadata including `CreationDate`
- **Online:** Upload to any PDF metadata viewer such as metadata2go.com

**Important:** The file system date (shown in your Downloads folder) will reflect the date you downloaded the file. This is normal. The *internal* PDF metadata date is what matters and is embedded inside the file itself.

## Current Corpus

The formal records have been updated since the original Zenodo deposits. Current versions reflect a formatting and reference standardization pass. **No mathematical content was changed.**

The corpus closed on April 20, 2026 (Easter Sunday) with FR11.

### Foundation

| Record | Title | Version |
|--------|-------|---------|
| FR1 | Three Primitives — Canonical Logic Sequence | v2.1 |
| FR2 | AI Cannot Govern AI | v2.1 |
| FR3 | ADCI Closure Theorem | v2.1 |

### Structural Lemmas

| Record | Title | Version |
|--------|-------|---------|
| FR4 | The Adjacency Lemma | v2.1 |
| FR5 | Lemma C — Ghost Authority Lemma | v2.1 |

### Closure Results

| Record | Title | Version |
|--------|-------|---------|
| FR6 | The Law of Declared Authority | v2.1 |
| FR7 | Bell Non-Closure | v2.1 |
| FR8 | Twisted Pair Legitimacy Theorem | v2.1 |

### Derived

| Record | Title | Version |
|--------|-------|---------|
| FR9 | AGI as a Decision-Complete System | v2.1 |
| FR10 | Primitive Stability Theorem | v1.3 |
| FR11 | The GBSH Correspondence | v1.7 |
| ILMM | Inclusive Lifelong Multistakeholder Model | v3.0 |

**Download current versions and ZIP:** [3primitives.io/formal_records](https://3primitives.io/formal_records/)

## Zenodo Restoration Status

- **Zenodo Ticket:** #3319104
- **Date of removal:** February 26, 2026
- **Affected account:** pyrateruby@gmail.com
- **Status as of April 10, 2026:** Unresolved. Escalated to CERN Service Desk.

## Licensing

- **ILMM:** CC BY 4.0
- **USS and PRRT:** CC BY-NC-SA 4.0

## Contact

- Stacy Gildenston & Pyrate Ruby Passell — delta@3primitives.io
- Website — [https://3primitives.io](https://3primitives.io)
