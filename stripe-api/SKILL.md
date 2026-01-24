---
name: stripe-api
description: The Stripe REST API. Please see https://stripe.com/docs/api for more details.. Use when working with the Stripe API or when the user needs to interact with this API.
metadata:
  api-version: "2026-01-28.clover"
  openapi-version: "3.0.0"
  contact: "dev-platform@stripe.com"
---

# Stripe API

The Stripe REST API. Please see https://stripe.com/docs/api for more details.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 77 resource index files
├── operations/     # 588 operation detail files
└── schemas/        # 153 schema groups, 1315 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://api.stripe.com/`

## Authentication

Supported methods: **basicAuth**, **bearerAuth**. See `references/authentication.md` for details.

## Resources

- **customers** → `references/resources/customers.md` (47 ops)
- **test_helpers** → `references/resources/test-helpers.md` (44 ops)
- **treasury** → `references/resources/treasury.md` (33 ops)
- **issuing** → `references/resources/issuing.md` (32 ops)
- **accounts** → `references/resources/accounts.md` (29 ops)
- **terminal** → `references/resources/terminal.md` (25 ops)
- **billing** → `references/resources/billing.md` (24 ops)
- **invoices** → `references/resources/invoices.md` (18 ops)
- **charges** → `references/resources/charges.md` (14 ops)
- **tax** → `references/resources/tax.md` (14 ops)
- **payment_intents** → `references/resources/payment-intents.md` (12 ops)
- **radar** → `references/resources/radar.md` (12 ops)
- **financial_connections** → `references/resources/financial-connections.md` (11 ops)
- **products** → `references/resources/products.md` (10 ops)
- **quotes** → `references/resources/quotes.md` (10 ops)
- **climate** → `references/resources/climate.md` (9 ops)
- **subscriptions** → `references/resources/subscriptions.md` (9 ops)
- **credit_notes** → `references/resources/credit-notes.md` (8 ops)
- **identity** → `references/resources/identity.md` (8 ops)
- **payment_records** → `references/resources/payment-records.md` (8 ops)
- **transfers** → `references/resources/transfers.md` (8 ops)
- **application_fees** → `references/resources/application-fees.md` (7 ops)
- **setup_intents** → `references/resources/setup-intents.md` (7 ops)
- **sources** → `references/resources/sources.md` (7 ops)
- **checkout** → `references/resources/checkout.md` (6 ops)
- **entitlements** → `references/resources/entitlements.md` (6 ops)
- **payment_methods** → `references/resources/payment-methods.md` (6 ops)
- **payouts** → `references/resources/payouts.md` (6 ops)
- **subscription_schedules** → `references/resources/subscription-schedules.md` (6 ops)
- **billing_portal** → `references/resources/billing-portal.md` (5 ops)
- **coupons** → `references/resources/coupons.md` (5 ops)
- **invoiceitems** → `references/resources/invoiceitems.md` (5 ops)
- **linked_accounts** → `references/resources/linked-accounts.md` (5 ops)
- **payment_links** → `references/resources/payment-links.md` (5 ops)
- **payment_method_domains** → `references/resources/payment-method-domains.md` (5 ops)
- **plans** → `references/resources/plans.md` (5 ops)
- **prices** → `references/resources/prices.md` (5 ops)
- **refunds** → `references/resources/refunds.md` (5 ops)
- **reporting** → `references/resources/reporting.md` (5 ops)
- **subscription_items** → `references/resources/subscription-items.md` (5 ops)
- **topups** → `references/resources/topups.md` (5 ops)
- **webhook_endpoints** → `references/resources/webhook-endpoints.md` (5 ops)
- **apple_pay** → `references/resources/apple-pay.md` (4 ops)
- **apps** → `references/resources/apps.md` (4 ops)
- **disputes** → `references/resources/disputes.md` (4 ops)
- **file_links** → `references/resources/file-links.md` (4 ops)
- **invoice_rendering_templates** → `references/resources/invoice-rendering-templates.md` (4 ops)
- **payment_method_configurations** → `references/resources/payment-method-configurations.md` (4 ops)
- **promotion_codes** → `references/resources/promotion-codes.md` (4 ops)
- **shipping_rates** → `references/resources/shipping-rates.md` (4 ops)
- **tax_ids** → `references/resources/tax-ids.md` (4 ops)
- **tax_rates** → `references/resources/tax-rates.md` (4 ops)
- **balance** → `references/resources/balance.md` (3 ops)
- **files** → `references/resources/files.md` (3 ops)
- **forwarding** → `references/resources/forwarding.md` (3 ops)
- **reviews** → `references/resources/reviews.md` (3 ops)
- **sigma** → `references/resources/sigma.md` (3 ops)
- **balance_settings** → `references/resources/balance-settings.md` (2 ops)
- **balance_transactions** → `references/resources/balance-transactions.md` (2 ops)
- **country_specs** → `references/resources/country-specs.md` (2 ops)
- **ephemeral_keys** → `references/resources/ephemeral-keys.md` (2 ops)
- **events** → `references/resources/events.md` (2 ops)
- **exchange_rates** → `references/resources/exchange-rates.md` (2 ops)
- **fabric** → `references/resources/fabric.md` (2 ops)
- **invoice_payments** → `references/resources/invoice-payments.md` (2 ops)
- **link_account_sessions** → `references/resources/link-account-sessions.md` (2 ops)
- **payment_attempt_records** → `references/resources/payment-attempt-records.md` (2 ops)
- **tax_codes** → `references/resources/tax-codes.md` (2 ops)
- **tokens** → `references/resources/tokens.md` (2 ops)
- **account** → `references/resources/account.md` (1 ops)
- **account_links** → `references/resources/account-links.md` (1 ops)
- **account_sessions** → `references/resources/account-sessions.md` (1 ops)
- **confirmation_tokens** → `references/resources/confirmation-tokens.md` (1 ops)
- **customer_sessions** → `references/resources/customer-sessions.md` (1 ops)
- **external_accounts** → `references/resources/external-accounts.md` (1 ops)
- **mandates** → `references/resources/mandates.md` (1 ops)
- **setup_attempts** → `references/resources/setup-attempts.md` (1 ops)
