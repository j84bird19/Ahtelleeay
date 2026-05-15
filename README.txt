Ahtelleeay V49.11 Backup + Recovery Lock Pass

Updates:
- Added Backup / Recovery Center to Banking > Trackers.
- Full portable database export as JSON.
- Full database import/restore for new phone, app reinstall, or app update recovery.
- Admin record receipt log for important saved entries.
- Optional backup email setting.
- Optional auto-open email receipt after major saves.
- Email unsent record receipts button.
- Download admin receipt log button.

Important note:
A browser/PWA cannot silently send email without a secure backend service. This build safely opens the device email/share app with a prefilled backup receipt so the user can send it. Full automatic background emailing will require a backend/email provider later.

Locked / untouched:
- Binder/navigation visuals.
- Banking/invoice sync logic.
- Financial precision.
- Savings goals math.
- Receipt/register UI.
- Supply sync.
- Schedule/Studio baseline.

Deployment rule:
Upload ONLY these extracted files into the branch root. Do not mix with older files.
