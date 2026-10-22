# Buyer discovery and due-diligence checklist

This document is for early, non-confidential scoping. It does **not** request credentials or proprietary code.

## Define the use case

- **Business need:** Which exact catalog/inventory/order workflow is blocked? What measurable result matters?
- **Current stack:** Commerce platform, ERP/WMS, payment service provider, documented integration APIs and permitted test environment.
- **Inventory:** SKU variations, quantities per warehouse, reservation semantics, stock source of truth and expected freshness.
- **Orders:** Placement, idempotency, refunds, cancellations, partial fulfilment and reconciliation.
- **Agent interaction:** Requested protocol and version, authentication, user consent and purchase confirmation.
- **Security and compliance:** Permission boundaries, data categories, retention requirements, secrets handling, audit evidence and relevant jurisdiction.
- **Operational readiness:** Rollback, monitoring, recovery objectives, support responsibilities and acceptance criteria.
- **Commercial matters:** Buyer entity, authority to sign, licensed components, IP ownership, timeline and proposed budget.

## A pilot requires, at minimum

1. A written scope and testable acceptance criteria.
2. Authorized synthetic or sandbox access and permission to test.
3. Validation of duplicate and concurrent orders, stock safety and retry handling.
4. Payment, receipt and refund flows checked against the specific merchant's obligations.
5. A documented threat model, test evidence, limitations and handover procedure.
6. Explicit commercial terms and any post-acceptance support agreement.

Private code review and commercial rights are discussed under a separate agreement. **No such review is implied to have been completed simply because this public showcase exists.**

For private business proposals: **agenticcommerce975@gmail.com**.
