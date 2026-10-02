# floor.b2a/v1

Agent-readable merchant catalog. Protocol `floor.b2a/v1`. No key.

- Catalog: https://floor-desk-ecru.vercel.app/api/catalog
- Desk: https://floor-desk-ecru.vercel.app
- Spec: https://github.com/manhatton31-svg/floor-b2a

Agents skip records with null return days, empty inventory, missing lead time, or fewer than six specs. Desk checkout is the paid SKU. Agent fills are not settled.
