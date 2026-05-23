Meridian V49.14 Android Receipt Upload Reliability Patch

Purpose:
- Fix receipt/image upload freezing inside Android WebView after selecting/taking a photo.
- Keep locked systems untouched.

Fixes:
- Compresses supply receipt photos before saving.
- Compresses bank receipt photos through the same reliable path.
- Compresses supply item/check photos to reduce localStorage/WebView load.
- Disables upload input during processing to prevent double-trigger freezes.
- Save on supply receipt now returns to Supplies > Receipts.
- Skips experimental auto-crop for now because scanner crop is not locked and can slow/freeze WebView.

Locked/untouched:
- Android wrapper code.
- Binder/navigation visuals.
- Banking/invoice/supply sync.
- Financial precision.
- Savings goals.
- Backup/report systems.

Deployment:
- Fully replace branch files with this extracted package.
- Hard refresh / clear app cache if WebView keeps old assets.
