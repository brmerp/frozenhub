# FrozenHub

Business Reporting Manager with integrated Cash & Carry sales and cost reports.

## Update GitHub

1. Extract this ZIP.
2. Open the existing brmerp/frozenhub repository.
3. Choose Add file > Upload files.
4. Upload index.html, sw.js and README.md into the repository root, replacing the existing files.
5. Commit changes. If your hosting is connected to this repository, wait for its deployment to finish.
6. Open the hosted app and refresh with Ctrl+F5.

Keep a Full Backup before updating. Do not upload backup JSON or additional Excel data to the public repository.

## Included changes

- Cash & Carry item/location/invoice reports and monthly salary allocation.
- Summary with CTN/KG cost, sale price, margins and total margin.
- Detail Report with freight, grocery and expense category breakup.
- Last available production-month cost fallback and item mappings.
- Formatted Excel export and column visibility/width controls.
- Login restoration improvements and temporary connection retry.
- Updated service worker cache version.

Cash & Carry uses the existing cloud integration. No new Supabase table is required by this update. Live deployment and cloud login still need to be checked after upload.

The HTML includes the sales data already present in the software. The existing repository is public, so these embedded figures will be visible in its source.
