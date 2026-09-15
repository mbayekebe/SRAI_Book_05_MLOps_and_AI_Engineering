# Installation Guide

## Repository placement

Copy the `PU-B05-C01` directory into the Book 5 production-unit collection without renaming its controlled files. Preserve the internal directories because cross-channel publication checks depend on them.

## Notebook verification

Open `notebook/V5_N01_mlops_foundations.ipynb` in a clean VS Code/Jupyter or Google Colab runtime and run all cells. Compare the regenerated evidence with the supplied canonical evidence. Small library-version differences may change serialized model hashes; they must be recorded rather than silently ignored.

## Presentation delivery

Use Presenter View so the narration embedded in the speaker-notes area is available to the presenter. Confirm fonts and charts on the target presentation platform before delivery.

## Publication control

Validate `release/SHA256SUMS.txt`, complete the unchecked approvals in `PUBLICATION_CHECKLIST.md`, and record the authorized decision in `RELEASE_RECORD.md`. Do not publish based solely on the presence of a ZIP file.
