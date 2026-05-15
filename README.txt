Ahtelleeay V49.12 Human-Readable Backup Reports

Baseline:
- Built from the locked V49.11 Backup + Recovery system.
- JSON full backup/import remains the true restore engine.

Added:
- Human-Readable Reports panel in Banking > Trackers.
- Business Records Report: balances, banking ledger, savings goals, invoices, spending categories.
- Client Report: client records, totals, invoices, payments.
- Schedule Snapshot: agenda/jobs/tasks and time logs.
- Reports open as styled printable/shareable HTML pages. User can print/save as PDF from the browser.
- Report exports are logged in the admin receipt log.

Locked / untouched:
- Binder/navigation visuals.
- Invoice <-> banking sync.
- Savings goals sync.
- Financial precision.
- Receipt/register UI.
- Supply sync.
- Full JSON backup/import recovery.

Important:
- Do not replace the JSON backup with visual reports. JSON is for restore. Reports are for human-readable records.

Deployment rule:
Delete existing files in the active branch and upload ONLY these extracted files into the repo root. Do not mix with older files.
