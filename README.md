# Paddy Business Manager

A mobile-friendly business tracker for a paddy seed / paddy buyback and packing workflow.

## Included modules
1. Program: organisation number, organiser, farmer, village, field/acreage, variety, bags issued, advance.
2. Buyback: bag-by-bag net weight, farmer, variety, lot, godown, rate, charges and advance adjustment.
3. Godown stock: stock by godown and variety; select bag records into cleaning batches.
4. Cleaning: machine, date, operator, input bags/weight, cleaned output and waste/reject weight.
5. Packing: 25 kg / 30 kg packets, lot, location and packing costs.
6. Sales: customer, variety, packet size, quantity, selling price, amount received and balance.
7. Backup: JSON backup/restore and CSV export.

## Publish using GitHub Pages
1. Create a new GitHub repository, for example `paddy-business-manager`.
2. Upload `index.html` to the repository root.
3. Open repository Settings → Pages.
4. Select deploy from the `main` branch and `/ (root)`, then save.
5. Open the GitHub Pages URL after deployment completes.

## Data safety
Transaction data is saved in localStorage in the browser on this device. GitHub Pages hosts the app code, not your records. Use Backup → Download Full Backup regularly and upload the JSON file to Google Drive. Verify that the backup file exists before clearing Chrome site data or switching devices. This starter app does not synchronise records between multiple phones.
