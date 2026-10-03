# Receipt Templates

Open:

**More → Receipt printer**

You can change the store name and receipt template.

## Supported placeholders

- `{store}`
- `{receipt}`
- `{date}`
- `{time}`
- `{datetime}`
- `{customer}`
- `{items}`
- `{item_count}`
- `{subtotal}`
- `{discount}`
- `{total}`
- `{payment}`
- `{paid}`
- `{balance}`
- `{change}`

## Example

```text
{store}
Receipt {receipt}
{datetime}
Customer: {customer}
--------------------------------
{items}
--------------------------------
TOTAL: {total}
Payment: {payment}
Paid: {paid}
Balance: {balance}
Change: {change}

Thank you!
```

Use **Reset template** to restore the default layout.
