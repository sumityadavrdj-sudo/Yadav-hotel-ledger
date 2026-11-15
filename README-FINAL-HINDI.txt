YADAV HOTEL LEDGER – FINAL PACKAGE

Files:
- yadav_hotel_ledger_new-1-1.html : final ledger app
- manifest.webmanifest : PWA app settings
- sw.js : updated offline cache (v3)
- icon-192.png / icon-512.png : existing Yadav Hotel icons

IMPORTANT DATA SAFETY
1. Before replacing anything, download a fresh JSON backup from your currently working Ledger.
2. Keep the existing index.html unchanged. Do not delete it.
3. Upload/replace yadav_hotel_ledger_new-1-1.html in the same GitHub repository path.
4. Replace manifest.webmanifest and sw.js with the files in this package. Keep the existing icon files.
5. Open the direct Ledger page once while online and refresh. If the old screen remains, close the tab and reopen after a short wait for the service worker update.
6. Check old records, sales, payments, cash expenses, worker expenses, and reports before using it for live entries.

DATA PRESERVATION
The app keeps the existing localStorage key: yadav_hotel_ledger_v1_new. It does not clear or rename that key. Old records are read in their existing format; legacy expenses and bank-method payments are retained. Restore replaces current data, so use it only with a verified backup.
