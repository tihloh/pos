# POS

A local-first Android point-of-sale and inventory application designed for fast barcode-driven retail workflows.

## Download

The latest signed APK is available from the **Releases** section of this repository.

This repository is the public home for:

- signed Android APK releases
- user documentation
- setup guides
- tutorials
- release notes

The application source code is maintained privately.

## Highlights

- Fast POS checkout
- Barcode and QR scanning
- Product catalog with images
- Inventory tracking
- Sales history and receipt reprinting
- Customer accounts
- Customer barcode lookup
- PhilID/ePhilID QR-assisted customer registration
- Cash, GCash, Maya, Card, and Account Payable modes
- Bluetooth and network ESC/POS receipt printing
- Editable receipt templates
- Optional central-server sync
- PIN and biometric/device-credential lock
- Local-first operation for offline use
- In-app update checking against this public repository

## Main sections

| Section | Purpose |
| --- | --- |
| POS | Search/scan products, select customers, checkout, print receipts |
| Sales | Review transactions, totals, payments, outstanding balances, and reprint receipts |
| Inventory | View stock movement and adjust quantities |
| Products | Manage items, barcodes, pricing, images, and suppliers |
| More | Customers, suppliers, printer settings, sync, appearance, updates, and app information |

## Customer accounts

Customers can be registered with a generated or manually assigned barcode. During checkout, a customer can be selected manually or found by scanning their barcode.

PhilID/ePhilID QR-assisted registration is also supported. The app asks for consent, reads supported PhilSys demographic fields, shows them for review, and prefills the customer form. The raw QR payload, PCN, and digital signature are not retained.

See [Customer Accounts](docs/customers.md) and [PhilID Registration](docs/philsys-registration.md).

## Account Payable

A sale can be saved as **Account Payable** for a registered customer. No immediate payment is required, and the unpaid amount remains visible as an outstanding balance in Sales.

See [Checkout and Account Payable](docs/checkout.md).

## Documentation

- [Installation and Updates](docs/installation.md)
- [Quick Start](docs/quick-start.md)
- [Products](docs/products.md)
- [Inventory](docs/inventory.md)
- [Customer Accounts](docs/customers.md)
- [PhilID/ePhilID Registration](docs/philsys-registration.md)
- [Checkout and Account Payable](docs/checkout.md)
- [Sales](docs/sales.md)
- [Receipt Printer Setup](docs/printer.md)
- [Receipt Templates](docs/receipt-templates.md)
- [Central Sync](docs/sync.md)
- [Privacy and Security](docs/privacy.md)
- [Troubleshooting](docs/troubleshooting.md)

## Platform

- Android 8.0+ (API 26+)
- Package: `com.tihloh.pos`

## Developer

**Christian Borsal Bustamante**  
Full Stack Software Developer  
IT Professional | Systems & Automation  
GitHub: **tihloh**
