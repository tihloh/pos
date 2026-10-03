# Central Sync

The app is local-first. Checkout, inventory, and product management use the local Room database.

Central sync is optional.

Open:

**More → Central sync**

Configure:

- Server URL
- Optional bearer token

The app can push a snapshot to:

`POST <server>/api/v1/sync`

The payload may include:

- products
- product images when locally stored and within the configured size limit
- suppliers
- customers
- sales

The current implementation is primarily a client-side push foundation. A compatible server endpoint is required.
