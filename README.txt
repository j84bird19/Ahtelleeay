Ahtelleeay V48.2 Math + Sync Lock Pass

Built from the confirmed-working V48.1 fixed binder/navigation frame.

Locked and preserved:
- Fixed binder/navigation frame
- All 5 side tabs fit and stay fixed
- Folder color engine
- Existing section architecture
- Offline-first PWA shell

V48.2 fixes only math/sync/save behavior:
- Central math normalization before save/flush
- Cost Per Unit recalculates from Cost ÷ Amount in real time
- Supply item page autosaves typed fields
- Quantity Remaining can be physically corrected with inventory correction log
- Invoice supply lines recalc from quantity × cost per unit
- Invoice totals, paid, balance, and status normalize before save
- Supply remaining resyncs after invoice edits/removals
- Quick Add supply path cleaned so duplicate supplies open correctly

Deployment rule:
Upload extracted files into the active dev branch as a complete replacement build.
