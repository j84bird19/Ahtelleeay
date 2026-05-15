Ahtelleeay V49.4 Banking Invoice + Supply Sync

Built from the locked V49 banking system.

Updates:
- Banking Accounts Money Received now includes a Link Unpaid Invoice dropdown.
- Selecting an unpaid/partial invoice autofills payment description and balance amount.
- Saving a linked banking income entry updates that invoice's paid amount/status.
- Mark Paid on an invoice creates a linked income entry in the checkbook register and prevents detached money tracking.
- Editing/deleting linked banking entries safely recalculates the linked invoice payment status.
- Banking Money Spent now includes a Supply Item dropdown populated from saved supplies.
- Selecting a supply autofills a supply purchase description/category and uses saved supply cost when available.

Locked / untouched:
- Banking register visuals and receipt thumbnail behavior.
- Binder/navigation/frame visuals.
- Financial precision engine.
- Supply quantity/invoice usage sync.
- Autosave/offline/PWA structure.

Not locked:
- Receipt scanner auto-crop remains experimental.

Deployment rule:
Delete existing files in the branch and upload ONLY these extracted files into the repo root.
