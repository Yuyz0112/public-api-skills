# GET /admin/api/unstable/discount_codes/lookup.json

**Resource:** [discounts/discountcode](../resources/discounts-discountcode.md)
**Retrieves the location of a discount code.
          The discount code's location is returned in the location header, not in the DiscountCode object itself.
            Depending on your HTTP client, the location of the discount code might follow the location header automatically.**
**Operation ID:** `deprecated_unstable_get_discount_codes_lookup`

https://shopify.dev/docs/admin-api/rest/reference/discounts/discountcode#lookup-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `code` | query | integer | No | code |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

