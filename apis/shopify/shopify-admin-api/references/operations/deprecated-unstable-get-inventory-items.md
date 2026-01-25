# GET /admin/api/unstable/inventory_items.json

**Resource:** [inventory/inventoryitem](../resources/inventory-inventoryitem.md)
**Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_unstable_get_inventory_items`

https://shopify.dev/docs/admin-api/rest/reference/inventory/inventoryitem#index-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids
                  required` | query | any | No | Show only inventory items specified by a comma-separated list of IDs.
                  (maximum: 100) |
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `ids` | query | integer | No | ids |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

