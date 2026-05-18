Meridian V49.13 Release Readiness Build

Baseline:
- Built from locked V49.12 Human-Readable Backup Reports.
- Preserves locked invoice/banking sync, supply sync, financial precision, autosave/offline storage, reports, backup/import, and binder navigation.

Added / Updated:
- Rebranded app shell, manifest, reports, backup labels, and reminders from Ahtelleeay to Meridian.
- Added Mobile/Desktop view toggle in the header. User preference saves locally.
- Added Quick Guide / Features tutorial from the header.
- Preserves blank first-run data model for new users. No demo data is seeded into the app.
- Existing local user data remains persistent through localStorage + IndexedDB mirror when the app is closed/reopened.
- Full Export/Import backup remains available in Banking > Trackers for app updates, device changes, and recovery.

Release checklist:
1. Delete existing files in the active branch.
2. Upload ONLY these extracted files into repo root.
3. Wait for deploy.
4. Hard refresh / clear service worker cache if needed.
5. Test new-user blank startup by clearing site data before opening.
6. Test close/reopen persistence.
7. Export a full backup before any major update.

Play Store note:
- This remains a PWA/web app build. For Play Store, wrap the hosted PWA using a Trusted Web Activity / Bubblewrap / Android Studio pipeline and submit the resulting .aab to Google Play Console.
