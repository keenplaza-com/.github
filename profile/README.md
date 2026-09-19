<img src="https://github.com/keenplaza-com/.github/raw/main/profile/logo.png" alt="" width="72" height="72" />

# KeenPlaza

Multi-tenant commerce **and** services platform for the Indian market — products and services in one cart.

A store signs up, gets its own catalog, storefront, pricing, stock, orders, payments and delivery, and runs all of it from one admin. The platform team runs every store from a console of its own.

## Repositories

| Repo | What it is |
| --- | --- |
| [core-engine](https://github.com/keenplaza-com/core-engine) | Go microservices behind one gateway: tenant, identity, catalog, pricing, inventory, cart, search, customer, order, payment, logistics |
| [tenant-admin-portal](https://github.com/keenplaza-com/tenant-admin-portal) | Where tenant staff run their business |
| [tenant-web-portal](https://github.com/keenplaza-com/tenant-web-portal) | Runtime serving each tenant's customer-facing storefront |
| [super-admin-portal](https://github.com/keenplaza-com/super-admin-portal) | Platform-internal console: tenants, leads, feature flags, audit log |
| [web-portal](https://github.com/keenplaza-com/web-portal) | Marketing site and lead capture |
| [tenant-app](https://github.com/keenplaza-com/tenant-app) | Customer mobile app (React Native) |
| [docs](https://github.com/keenplaza-com/docs) | Architecture, module specs and ADRs |

## Platform at a glance

- **One cart for products and services** — buy, book, install, repair, maintain.
- **Per-tenant isolation** — Postgres row-level security on every query, one gateway at the edge.
- **Server-authoritative money** — offers, coupons, GST and delivery fees computed by the pricing service, never the client.
- **Stock you can trust** — per-warehouse ledger, checkout holds that expire on their own, transfers.
- **Cash or online** — COD and each store's own Razorpay account.
- **Delivery, tracked** — Blue Dart booking and tracking, or any courier by hand.

Go · React 19 · TypeScript · Postgres · Kubernetes
