# subscription_schedule_phase_configuration

A phase describes the plans, coupon, and trialing status of a subscription for a predefined time period.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `add_invoice_items` | subscription_schedule_add_invoice_item[] | Yes | A list of prices and quantities that will generate invoice items appended to the next invoice for this phase. |
| `application_fee_percent` | number | No | A non-negative decimal between 0 and 100, with at most two decimal places. This represents the percentage of the subscription invoice total that will be transferred to the application owner's Stripe account during this phase of the schedule. |
| `automatic_tax` | [schedules_phase_automatic_tax](schedules-phase-automatic-tax.md) | No |  |
| `billing_cycle_anchor` | enum: automatic, phase_start | No | Possible values are `phase_start` or `automatic`. If `phase_start` then billing cycle anchor of the subscription is set to the start of the phase when entering the phase. If `automatic` then the billing cycle anchor is automatically modified as needed when entering the phase. For more information, see the billing cycle [documentation](https://docs.stripe.com/billing/subscriptions/billing-cycle). |
| `billing_thresholds` | any | No | Define thresholds at which an invoice will be sent, and the subscription advanced to a new billing period |
| `collection_method` | enum: charge_automatically, send_invoice | No | Either `charge_automatically`, or `send_invoice`. When charging automatically, Stripe will attempt to pay the underlying subscription at the end of each billing cycle using the default source attached to the customer. When sending an invoice, Stripe will email your customer an invoice with payment instructions and mark the subscription as `active`. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `default_payment_method` | any | No | ID of the default payment method for the subscription schedule. It must belong to the customer associated with the subscription schedule. If not set, invoices will use the default payment method in the customer's invoice settings. |
| `default_tax_rates` | tax_rate[] | No | The default tax rates to apply to the subscription during this phase of the subscription schedule. |
| `description` | string | No | Subscription description, meant to be displayable to the customer. Use this field to optionally store an explanation of the subscription for rendering in Stripe surfaces and certain local payment methods UIs. |
| `discounts` | discounts_resource_stackable_discount[] | Yes | The stackable discounts that will be applied to the subscription on this phase. Subscription item discounts are applied before subscription discounts. |
| `end_date` | integer (unix-time) | Yes | The end of this phase of the subscription schedule. |
| `invoice_settings` | any | No | The invoice settings applicable during this phase. |
| `items` | subscription_schedule_configuration_item[] | Yes | Subscription items to configure the subscription to during this phase of the subscription schedule. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to a phase. Metadata on a schedule's phase will update the underlying subscription's `metadata` when the phase is entered. Updating the underlying subscription's `metadata` directly will not affect the current phase's `metadata`. |
| `on_behalf_of` | any | No | The account (if any) the charge was made on behalf of for charges associated with the schedule's subscription. See the Connect documentation for details. |
| `proration_behavior` | enum: always_invoice, create_prorations, none | Yes | When transitioning phases, controls how prorations are handled (if any). Possible values are `create_prorations`, `none`, and `always_invoice`. |
| `start_date` | integer (unix-time) | Yes | The start of this phase of the subscription schedule. |
| `transfer_data` | any | No | The account (if any) the associated subscription's payments will be attributed to for tax reporting, and where funds from each payment will be transferred to for each of the subscription's invoices. |
| `trial_end` | integer (unix-time) | No | When the trial ends within the phase. |

