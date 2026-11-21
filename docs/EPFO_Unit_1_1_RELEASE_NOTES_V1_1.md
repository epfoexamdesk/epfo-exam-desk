# EPFO Exam Desk — Unit 1.1 V1.1 Review Release

## Release type
Review candidate; not published to production.

## Safety guarantee
This release is intended for a new branch only. Do not overwrite `main` directly. The existing live site remains unchanged until the owner reviews and merges a pull request.

## Proposed branch
`release/unit-1-1-v1.1-review`

## Proposed files
- `index.html` — corrected standalone Unit 1.1 learning portal
- `docs/EPFO_Unit_1_1_Academic_Correction_Report_V1_1.md`
- `docs/EPFO_Unit_1_1_PYQ_Provenance_Register_V1_1.md`
- `docs/EPFO_Unit_1_1_QA_Report_V1_1.md`

## Preserved
- Nine-section navigation and content architecture
- Interactive question checking
- Eight practice questions (clearly labelled PYQ-style; provenance pending)
- Five MCQs
- Ten interactive flashcards
- Existing WhatsApp contact number and enquiry message
- Responsive, dependency-free HTML/CSS/JavaScript implementation

## Key corrections
- Code on Social Security, 2020 sections 20(1)(a), 21, 23(1), 23(3), 122, 127 and 128
- Distinction between EPF ₹25,000 notified wage ceiling and EPS ₹15,000 Central Government contribution ceiling
- Current 2026 EPF, EPS and EDLI scheme treatment, with amendments/corrigenda
- Legacy scheme facts identified as legacy rather than current law

## Release gates before merge
1. Authenticate the eight claimed PYQs against original UPSC papers and official keys, or retain their practice-only labels.
2. Verify ELI/PM-VBRY and auto-settlement statements against primary official material before adding them back as factual claims.
3. Browser-test desktop and mobile layouts.
4. Test every nav item, quiz answer, flashcard and WhatsApp enquiry link.
5. Review legal content and source links.
6. Confirm official e-Gazette PDFs/corrigenda and replace or supplement third-party mirror links.
7. Merge only after owner approval.

## GitHub publication status
Not published. Uploaded to `release/unit-1-1-v1.1-review` and submitted as draft PR #1 against `main`. Six release files are present. No merge or deployment has occurred; `main` remains unchanged.