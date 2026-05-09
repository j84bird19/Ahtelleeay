Ahtelleeay V48.3 Math + Sync Stabilization

Baseline:
- Built from confirmed working V48.1 visual/folder-frame baseline.
- Binder/frame/tab CSS was not redesigned or replaced.
- This pass is intended to patch math/sync behavior only.

Locked / untouched:
- Fixed binder/navigation frame
- Five vertical section tabs
- Section color engine
- Mobile layout shell
- Studio visuals

Updates:
- Cost Per Unit recalculates from Cost ÷ Amount of Item for That Cost.
- Supply item fields autosave while typing.
- Quantity Remaining can be corrected using a physical count.
- Manual remaining corrections are logged as inventory adjustments.
- Invoice supply lines normalize quantity × cost per unit when a saved supply has a unit cost.
- Invoice total, paid, balance, and status normalize before save and flush.
- Supply remaining reconciles after invoice add/edit/remove/autosave.
- Quick Add duplicate-supply path cleaned so it opens the existing item instead of injecting boot code.

Deployment rule:
Upload ONLY these extracted files into the repo root of the active dev branch. Do not mix with older files.
