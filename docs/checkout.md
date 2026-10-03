# Checkout and Account Payable

## Supported payment modes

- Cash
- GCash
- Maya
- Card
- Account Payable

## Cash

Enter the amount received or use:

- **Exact**
- **+ ₱100**

The app calculates change automatically.

## E-wallet / Card

For GCash, Maya, and Card, an optional reference value can be stored.

## Account Payable

Account Payable is for sales charged to a registered customer.

Requirements:

- A registered customer must be selected.
- Immediate payment is recorded as ₱0.
- The full sale amount becomes outstanding.
- The sale is marked as `ACCOUNT_PAYABLE`.

The checkout button changes to **Save to Account**.

The outstanding amount is calculated from:

`Total - Amount Paid`

Sales history displays the remaining balance.
