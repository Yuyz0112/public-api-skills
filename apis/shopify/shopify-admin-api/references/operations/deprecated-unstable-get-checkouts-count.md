# GET /admin/api/unstable/checkouts/count.json

**Resource:** [orders/abandoned-checkouts](../resources/orders-abandoned-checkouts.md)
**Retrieves a count of checkouts from the past 90 days**
**Operation ID:** `deprecated_unstable_get_checkouts_count`

https://shopify.dev/docs/admin-api/rest/reference/orders/abandoned-checkouts#count-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `created_at_min` | query | any | No | Count checkouts created after the specified date. (format: 2014-04-25T16:15:47-04:00) |
| `created_at_max` | query | any | No | Count checkouts created before the specified date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_min` | query | any | No | Count checkouts last updated after the specified date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_max` | query | any | No | Count checkouts last updated before the specified date. (format: 2014-04-25T16:15:47-04:00) |
| `status` | query | any | No | Count checkouts with a given status.
                  (default: open)
                    
                        open: Count only open abandoned checkouts.
                        closed: Count only closed abandoned checkouts. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

