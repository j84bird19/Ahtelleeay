Ahtelleeay V48.4 Invoice Supply Charge Fix

Baseline:
- Built from confirmed working V48.3 branch structure.
- Binder/frame/tab visuals remain locked and untouched.
- This patch only fixes invoice supply charge calculation.

Locked / untouched:
- Fixed binder/navigation frame
- Five vertical section tabs
- Section color engine
- Mobile layout shell
- Studio visuals

Updates:
- Invoice supplies now calculate charge from saved Cost Per Unit × Amount Used.
- Invoice supply lines can pull Cost Per Unit even if it was not cached yet but Cost and Amount For That Cost exist.
- Named supply items are promoted out of draft status so invoice lookup can find them.
- Duplicate quick-add / invoice-added supplies resolve to the existing saved supply instead of creating a $0 duplicate.

Deployment rule:
Upload ONLY these extracted files into the repo root of the active dev branch. Do not mix with older files.
