Ahtelleeay V49.6 Invoice Payment Controls + Location Pin

Built from the locked V49.5 banking/schedule build.

Locked / untouched:
- Binder/navigation/frame visuals.
- Banking register and receipt thumbnail behavior.
- Financial precision.
- Invoice/supply quantity usage sync.
- Autosave/offline/PWA structure.
- Banking invoice/supply sync architecture.

Updates:
- Invoice Amount Paid fields are now editable without the page fighting/re-rendering while typing.
- Invoice Status is now a dropdown: UNPAID, PARTIAL, PAID.
- Setting status to PAID creates/updates the linked Banking income entry and keeps invoice/banking totals synced.
- Setting status to UNPAID removes auto-created invoice payment entries and recalculates invoice paid/status safely.
- Full invoice view and embedded client invoice view both use the same payment/status sync behavior.
- Job form address area now includes Pin Current Location and Open Map buttons for job sites without clear addresses.
- Pinned GPS coordinates are saved with the job draft/job record and can open in Google Maps.

Deployment rule:
Delete existing files in the active dev branch and upload ONLY these extracted files into the repo root.


V49.7 Savings Goals:
- Adds savings goals to Banking Trackers with Total Needed, Amount Saved Toward, Priority, remaining amount, and progress bars.
- Goal allocations sync with actual savings balance so allocated savings does not create fake money.
- Unallocated savings tracker updates from banking transfer entries.
- Binder, invoice, supply, and banking register locked systems preserved.


V49.8 Fixes:
- Rebuilt invoice payment to banking ledger sync as a canonical bridge.
- Editing invoice Amount Paid creates/updates one linked banking income entry.
- Marking invoice PAID updates the linked ledger entry instead of creating duplicates.
- Banking income entries linked to invoices update invoice paid/status.
- Deleting linked ledger entries recalculates invoice status safely.


V49.9 Updates:
- Banking income invoice link now shows ANY invoice, not only unpaid/partial invoices.
- Dropdown labels show invoice status, paid, total, and balance so existing payments can be matched.
- Selecting an already-linked invoice updates/merges the existing ledger entry instead of creating duplicates.
- Paid invoices can be linked to a bank entry for cleanup/reconciliation.
- Locked systems untouched: binder visuals, receipts/register UI, savings goals, supply math, financial precision, autosave/offline shell.
