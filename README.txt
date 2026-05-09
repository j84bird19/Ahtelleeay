Ahtelleeay V48 Foundation Rebuild

Purpose:
- Clean rebuild from the stable V47 baseline.
- Replaces the stacked V16/V17/V18 visual tab engines with ONE clean binder/folder engine.
- Keeps all existing app logic intact.

Updates:
- Fixed binder/navigation frame so header, option tabs, and vertical section tabs remain fixed while page content scrolls.
- Rebuilt vertical section tabs as 5 equal full-height overlapping physical folder tabs.
- Rebuilt top option tabs with luxury gold/section-colored folder styling.
- Active section colors the folder frame/background.
- Cleaned mobile layout to prevent visual-engine conflict and white-screen risk.
- Updated cache/service worker/build references to V48.

Deployment rule:
Upload ONLY these extracted files into the repo root. Do not mix with older files.
