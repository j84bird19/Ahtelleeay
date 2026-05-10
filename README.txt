Ahtelleeay V48.8 Studio Engine Fix

Baseline:
- Built from V48.7 Studio polish build.
- Binder/frame, tabs, autosave, supply/invoice math, financial precision, and offline structure are untouched.

Fixes:
- Pencil/eraser strokes now render as continuous smooth strokes instead of broken dashed segments.
- Studio color changes apply immediately to new drawing strokes.
- Replaced Android native color dialog with an in-app palette + hex color field.
- Opacity and size controls remain in the Style menu.
- File and camera image import remain available.

Deployment rule:
Upload ONLY these extracted files into the repo root of the active dev branch. Do not mix with older files.
