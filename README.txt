Ahtelleeay V49.3 Receipt Thumbnail + Scanner Crop

Baseline:
- Built from confirmed working V49.2 Banking Receipt Save Fix.
- Banking V1 remains locked.
- Binder/frame, tabs, colors, math, sync, autosave, and offline shell are untouched.

Updates:
- Receipt thumbnails in Banking Receipts are constrained to a fixed small size so entry boxes do not resize.
- Tapping/opening a receipt entry shows the larger receipt image in the edit view.
- Tapping the full receipt image opens a larger viewer overlay.
- Receipt image upload now runs a lightweight scanner-style auto-crop pass to trim document/receipt edges when detectable.
- Image compression remains enabled to prevent large camera photos from freezing the app.

Note:
- Auto-crop is a browser-safe beta heuristic. It works best when the receipt/card/document has visible contrast from the surface behind it.

Deployment rule:
Upload ONLY these extracted files into the repo root of the active banking branch. Do not mix with older files.
