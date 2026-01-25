# PUT /admin/api/unstable/recurring_application_charges/{recurring_application_charge_id}/customize.json

**Resource:** [billing/recurringapplicationcharge](../resources/billing-recurringapplicationcharge.md)
**Updates the capped amount of an active recurring application charge**
**Operation ID:** `deprecated_unstable_update_recurring_application_charges_param_recurring_application_charge_id_customize`

https://shopify.dev/docs/admin-api/rest/reference/billing/recurringapplicationcharge#customize-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `recurring_application_charge_id` | path | string | Yes | recurring_application_charge_id |
| `recurring_application_charge[capped_amount]` | query | integer | No | recurring_application_charge[capped_amount] |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

