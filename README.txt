Ahtelleeay V48.5 Currency Precision Fix

Baseline:
- Built from confirmed working V48.4 invoice supply charge build.
- Binder/frame/tab visuals are untouched.
- This pass only normalizes currency precision.

Locked / untouched:
- Fixed binder/navigation frame
- Five vertical section tabs
- Section color engine
- Mobile layout shell
- Studio visuals
- Supply quantity syncing
- Invoice supply charge logic

Updates:
- Invoice supply line charges now use displayed currency precision.
- Hidden 4-decimal Cost Per Unit values no longer make invoice totals disagree with visible line math.
- Invoice totals, paid values, balances, and status use deterministic cents-based rounding.
- Money display now uses the same cents normalization everywhere.

Example:
- 3 × $0.53 = $1.59
- 1 × $0.83 = $0.83
- Invoice total = $2.42

Deployment rule:
Upload ONLY these extracted files into the repo root of the active dev branch. Do not mix with older files.


V48.6 Save / Autosave Hardening:
- Adds live draft autosave for job, event, client, invoice, supply, and timecard input fields.
- Flushes visible page fields before page hide/app close.
- Persists invoice pending service/supply inputs as drafts until explicitly added or committed on navigation.
- Preserves locked binder visuals and locked financial precision engine.
