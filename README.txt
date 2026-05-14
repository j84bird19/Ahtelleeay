Ahtelleeay V49.2 Banking Receipt Save Fix

Baseline:
- Built from working V49.1 Banking Account Register build.
- Binder/frame visuals are untouched.
- Banking input/register flow is preserved.

Fixes:
- Receipt photo attachments are resized/compressed before saving so large camera photos do not freeze the app or exceed localStorage limits.
- Save on a banking entry now returns to Banking > Accounts.
- Receipt photo save persists offline through the existing save/offline mirror flow.

Deployment rule:
Upload ONLY these extracted files into the repo root of the active dev branch. Do not mix with older files.
