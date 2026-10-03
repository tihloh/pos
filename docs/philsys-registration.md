# PhilID / ePhilID Assisted Registration

The app can use a PhilID/ePhilID QR code to help prefill a customer account.

## Flow

1. Open **More → Customers**.
2. Tap **PhilID**.
3. Review the consent notice with the customer.
4. Tap **Consent given · Scan**.
5. Scan the PhilID/ePhilID QR.
6. Review the detected information.
7. Tap **Use for customer**.
8. Complete any remaining customer fields and save.

## Supported QR structure

The parser expects the PSA PhilSys signed JSON structure, including fields such as:

- `Issuer`
- `DateIssued`
- `subject.fName`
- `subject.mName`
- `subject.lName`
- `subject.Suffix`
- `subject.sex`
- `subject.DOB`
- `subject.POB`
- `alg`
- `signature`

The app currently expects `Issuer = PSA` and `alg = EDDSA`.

## Privacy behavior

The app does **not** retain:

- raw PhilSys QR payload
- PCN
- digital signature

The QR is used only to assist customer registration.

## Verification status

Parsing the documented structure is not the same as cryptographic verification.

A customer imported from a PhilSys QR is marked as imported from PhilSys but **not cryptographically verified** unless a future official verification integration is added.
