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
