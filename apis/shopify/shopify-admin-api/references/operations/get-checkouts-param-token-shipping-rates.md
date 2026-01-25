# GET /admin/api/2020-10/checkouts/{token}/shipping_rates.json

**Resource:** [sales-channels/checkout](../resources/sales-channels-checkout.md)
**Retrieves a list of available shipping rates for the specified checkout. Implementers need to poll this endpoint until rates become available.
    Each shipping rate contains the checkout's new subtotal price, total tax, and total price in the event that this shipping rate is selected. This can be used to update the UI without performing further API requests.
    To apply a shipping rate, update the checkout's shipping line with the handle of the selected rate.**
**Operation ID:** `get_checkouts_param_token_shipping_rates`

https://shopify.dev/docs/admin-api/rest/reference/sales-channels/checkout#shipping_rates-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | path | string | Yes | token |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

