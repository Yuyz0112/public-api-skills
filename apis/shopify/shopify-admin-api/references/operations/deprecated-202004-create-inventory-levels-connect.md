# POST /admin/api/2020-04/inventory_levels/connect.json

**Resource:** [inventory/inventorylevel](../resources/inventory-inventorylevel.md)
**Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations.**
**Operation ID:** `deprecated_202004_create_inventory_levels_connect`

https://shopify.dev/docs/admin-api/rest/reference/inventory/inventorylevel#connect-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `inventory_item_id
                  required` | query | any | No | The ID of the inventory item. |
| `location_id
                  required` | query | any | No | The ID of the location that the inventory level belongs to. To find the ID of the location, use the Location resource. |
| `relocate_if_necessary` | query | any | No | Whether inventory for any previously connected locations will be relocated. This property is ignored when no fulfillment service location is involved. For more information, see Inventory levels and fulfillment service locations.
                  (default: false) |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

