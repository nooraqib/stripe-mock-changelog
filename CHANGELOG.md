# Stripe API Changelog

## 2026-08-08 — v2026-08-08
- **Breaking:** Removed support for `stripe.charges.create()`. Use `stripe.paymentIntents.create()` instead. Existing integrations calling the Charges API will fail after 2026-11-01.

## 2026-08-01 — v2026-08-01
- Added `metadata.source` to Charge objects. Non-breaking.

## 2026-07-15 — v2026-07-15
- Improved idempotency key handling. Non-breaking.
