# POST /admin/api/2020-01/inventory_levels/set.json

**Resource:** [inventory/inventorylevel](../resources/inventory-inventorylevel.md)
**Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations.**
**Operation ID:** `deprecated_202001_create_inventory_levels_set`

https://shopify.dev/docs/admin-api/rest/reference/inventory/inventorylevel#set-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `inventory_item_id
                  required` | query | any | No | The ID for the inventory item. |
| `location_id
                  required` | query | any | No | The ID of the location that the inventory level belongs to. To find the ID of the location, use the Location resource. |
| `available
                  required` | query | any | No | Sets the available inventory quantity. |
| `disconnect_if_necessary` | query | any | No | Whether inventory for any previously connected locations will be set to 0 and the locations disconnected. This property is ignored when no fulfillment service  is involved. For more information, see Inventory levels and fulfillment service locations.
                  (default: false) |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

