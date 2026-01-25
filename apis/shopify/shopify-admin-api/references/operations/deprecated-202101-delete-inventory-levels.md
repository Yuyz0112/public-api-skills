# DELETE /admin/api/2021-01/inventory_levels.json

**Resource:** [inventory/inventorylevel](../resources/inventory-inventorylevel.md)
**Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level.**
**Operation ID:** `deprecated_202101_delete_inventory_levels`

https://shopify.dev/docs/admin-api/rest/reference/inventory/inventorylevel#destroy-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `inventory_item_id
                  required` | query | any | No | The ID for the inventory item. |
| `location_id
                  required` | query | any | No | The ID of the location that the inventory level belongs to. To find the ID of the location, use the Location resource. |
| `inventory_item_id` | query | integer | No | inventory_item_id |
| `location_id` | query | integer | No | location_id |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

