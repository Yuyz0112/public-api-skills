# GET /admin/api/2020-01/price_rules/{price_rule_id}/batch/{batch_id}/discount_codes.json

**Resource:** [discounts/discountcode](../resources/discounts-discountcode.md)
**Retrieves a list of discount codes for a discount code creation job.
          Discount codes that have been successfully created include a populated id field. Discount codes that
          encountered errors during the creation process include a populated errors field.**
**Operation ID:** `deprecated_202001_get_price_rules_param_price_rule_id_batch_param_batch_id_discount_codes`

https://shopify.dev/docs/admin-api/rest/reference/discounts/discountcode#batch_discount_codes_index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `price_rule_id` | path | string | Yes | price_rule_id |
| `batch_id` | path | string | Yes | batch_id |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

