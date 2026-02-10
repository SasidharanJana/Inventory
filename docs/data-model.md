# Core Data Model

## Entity Highlights
- **Tenant**: organization, industry template, billing, and branding settings.
- **User & Role**: RBAC, permission scopes, and audit metadata.
- **Location**: warehouse, store, facility, or virtual location.
- **Item**: SKU, variants, unit of measure, valuation method.
- **Inventory Ledger**: immutable stock movement events.
- **Supplier & Customer**: contacts, contracts, pricing, terms.
- **Procurement**: RFQ → Purchase Order → Receipt → Invoice.
- **Sales**: Quote → Sales Order → Shipment → Invoice/Return.
- **Finance**: journal entries, GL mappings, tax rules.
- **HR**: employee profile, role assignments, time tracking.

## Inventory Ledger (Event Sourcing)
- **Inbound**: purchase receipts, production completions, transfers.
- **Outbound**: sales shipments, scrap, adjustments.
- **Adjustments**: cycle counts, audit corrections, expirations.

## Profit & Loss
- Track revenue, COGS, operating expenses, and gross margin.
- P&L reporting by product line, customer segment, location, and time.

## Extensibility
- **Custom Entities** for specialized industry needs.
- **Entity Relationships** allow linking assets, compliance docs, or certifications.
