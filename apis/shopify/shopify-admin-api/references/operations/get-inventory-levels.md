# GET /admin/api/2020-10/inventory_levels.json

**Resource:** [inventory/inventorylevel](../resources/inventory-inventorylevel.md)
**Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `get_inventory_levels`

https://shopify.dev/docs/admin-api/rest/reference/inventory/inventorylevel#index-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `inventory_item_ids` | query | any | No | A comma-separated list of inventory item IDs.
                  (maximum: 50) |
| `location_ids` | query | any | No | A comma-separated list of location IDs. To find the ID of a location, use the Location resource.
                  (maximum: 50) |
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `updated_at_min` | query | any | No | Show inventory levels updated at or after date (format: 2019-03-19T01:21:44-04:00). |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

