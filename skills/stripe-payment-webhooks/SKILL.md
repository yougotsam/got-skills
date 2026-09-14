---
name: stripe-payment-webhooks
description: Use when handling Stripe webhook events. Sync payments to your database reliably.
source: yougotsam/lovable-skills
category: ["backend", "payments"]
tags: ["stripe", "webhooks", "payments"]
difficulty: intermediate
version: "1.0.0"
related: ["payment-webhook-idempotency", "payment-webhook-testing"]
---

# Stripe Payment Webhooks

Handle Stripe webhooks to sync payment events (charges, subscriptions, invoices) to your database.

## When to Use

Processing Stripe events: charge.succeeded, customer.subscription.updated, invoice.payment_succeeded.

## Key Patterns

- Verify webhook signature (critical for security)
- Idempotent handlers (use `idempotency_key`)
- Log all events before processing
- Handle retries gracefully

## Common Traps

- Stripe sends events multiple times (need idempotency)
- Deno crypto differs from Node.js
- Not testing with Stripe CLI locally

## Related Skills

- `payment-webhook-idempotency` — Handling duplicate events
- `payment-webhook-testing` — Local testing patterns
- `payment-failed-and-recovery` — Handling failures

---

*Source: yougotsam/lovable-skills*
