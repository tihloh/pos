# Troubleshooting

## Barcode is not found

- Confirm the saved barcode is correct.
- Try scanning again with the code centered in the scanner frame.
- Check whether the product/customer exists locally.
- UPC-A and EAN-13 leading-zero variants are handled for products.

## Product has no image

Edit the product and choose an image from the device.

## Bluetooth printer is missing

- Pair the printer in Android settings first.
- Grant Bluetooth permission when requested.
- Return to **More → Receipt printer** and refresh paired devices.

## Network printer does not print

Check:

- printer IP address
- same local network
- TCP port, commonly 9100
- firewall/router restrictions

## Update will not install

Android may require permission to install unknown apps for the POS app or the component launching the installer.

Some Android versions still require the system installation confirmation even when the APK has already been downloaded internally.

## Account Payable is unavailable

Select a registered customer first. Account Payable cannot be assigned to a Walk-in sale.

## PhilID QR is rejected

The current parser expects the PSA PhilSys signed JSON structure with `Issuer = PSA` and `alg = EDDSA`.

Damaged, unsupported, or differently formatted QR payloads may not be accepted.
