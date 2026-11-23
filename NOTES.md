## Gold Bills 2.4.2

**Fixes found while testing with sample Indian bills:**

- **GST no longer doubled.** When the phone's reader returned the CGST and SGST lines twice, they were added up twice (3% became 6%). Each tax line now counts once.
- **A bill that doesn't add up stays flagged after saving.** Each item of a multi-item bill now keeps the bill's printed total, and every item shows ⚠ until the items add up to it (or a missing item is added). Works on Android and Windows.
- **Gold value misread as "0".** The gold rate is now worked out from weight × rate + making = amount, instead of taking the making charge per gram as the rate.
- **Cleaner item names.** Stray characters such as ".}" or ")" from the reader are removed.
- **New: Delete all bills** (Android: Settings → Your data, with Undo until you close the app; Windows: toolbar, with Undo straight after).

Bills saved with an earlier version keep what was saved: delete and re-add any multi-item bill to get these checks.
