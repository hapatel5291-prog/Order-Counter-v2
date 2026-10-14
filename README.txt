SMART ORDER COUNTER — ANDROID PACKAGE

This is a universal, phone-first web app/PWA source package, not an APK file.

INCLUDED
- Fast one-tap sale recording with numbered menu buttons.
- Cash or Online/UPI payment choice, recorded per sale.
- Automatic local date, time, item, category and price capture.
- Today dashboard: item count, sales, cash total, online total and item-wise revenue.
- Sales history with date range, item search and payment filter.
- Custom CSV report by start/end date AND time, with payment/item filters and a summary.
- Universal menu settings: title, subtitle, currency, add/remove items, edit item names/prices/categories, enable/disable buttons.
- Import menu CSV and download a menu template.
- Export all sales to CSV.
- Download/restore a full JSON backup.
- Undo last sale and delete individual sales.
- Clear all sales with two confirmation prompts.

DEFAULT MENU
1 Regular Khichu ₹40
2 Khichu Bites ₹50
3 Butter Corn ₹40
4 Butter Corn Chaat ₹60
5 Cheese Butter Corn Chaat ₹80

IMPORTANT DATA NOTE
Data is saved locally in the browser storage on this phone. It does not automatically sync to another device. Download a full backup regularly. Clearing browser storage can erase records.

HOW TO INSTALL ON ANDROID
For an installable home-screen app with offline support, the files need to be hosted on an HTTPS website:
1. Extract the ZIP on a computer.
2. Upload index.html, manifest.json and sw.js to an HTTPS static host (for example GitHub Pages or Netlify).
3. Open the hosted site in Chrome on Android.
4. Chrome menu -> Add to Home screen / Install app.
5. Open it from the home-screen icon.

Opening index.html directly can let you test it in a browser, but browser restrictions mean PWA install/offline features may not work from a local file. This package is not a compiled APK.

MENU CSV FORMAT
Number,Name,Price,Category,Enabled
1,Regular Khichu,40,Khichu,true
2,Khichu Bites,50,Khichu,true
3,Butter Corn,40,Sweet Corn,true
4,Butter Corn Chaat,60,Sweet Corn,true
5,Cheese Butter Corn Chaat,80,Sweet Corn,true

NEW IN THIS VERSION
After each sale is recorded, a compact confirmation appears for about one second and identifies the item, price, and selected payment method. It does not change the sale workflow or stored data.


NEW FEATURE — QUICK LUMP-SUM ADJUSTMENT
Open Today, enter an amount, choose Add or Remove, select Cash or Online/UPI, optionally add a reason, then tap Save adjustment. Adjustments are stored separately from item sales and included in the cash/online collection-after-adjustments figures. You can delete a mistaken adjustment from the list. Full JSON backups include adjustments; restoring an older backup without adjustments will keep the adjustment list empty.


Latest update: quick quantity presets (1, 2, 3, 5 or custom 1-99), automatic reset to quantity 1 after each tap, grouped last 5 transaction actions, batch-aware Undo, and expanded Today dashboard with product quantity/revenue, category totals, and product-by-payment breakdown.
