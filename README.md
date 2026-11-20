# Stockroom

A browser-based shop inventory and checkout app based on the supplied Stockroom HTML.

## Features

- Shopkeeper account creation and login screen
- Per-account inventory, sales history, and browser-local persistence
- Add/edit products with SKU/barcode code, quantity, reorder threshold, and price
- Low-stock and out-of-stock statuses update automatically
- Checkout cart with quantity controls, stock validation, and automatic stock deduction
- Sales history for completed bills
- Camera barcode scanning when supported, plus keyboard/USB scanner or manual SKU entry

## Data note

This is a standalone front-end demo. Accounts and data are stored in the browser's local storage on the current device. Passwords are not protected by a server and there is no cloud sync or multi-device account security. For a production shop system, connect a secure authentication service and database.
