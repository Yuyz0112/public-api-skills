# POST /admin/api/2021-01/inventory_levels/adjust.json

**Resource:** [inventory/inventorylevel](../resources/inventory-inventorylevel.md)
**Adjusts the inventory level of an inventory item at a single location**
**Operation ID:** `deprecated_202101_create_inventory_levels_adjust`

https://shopify.dev/docs/admin-api/rest/reference/inventory/inventorylevel#adjust-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `inventory_item_id
                  required` | query | any | No | The ID of the inventory item. |
| `location_id
                  required` | query | any | No | The ID of the location that the inventory level belongs to. To find the ID of the location, use the Location resource. |
| `available_adjustment
                  required` | query | any | No | The amount to adjust the available inventory quantity. Send negative values to subtract from the current available quantity. For example, "available_adjustment": 2 increases the current available quantity by 2, and "available_adjustment": -3decreases the current available quantity by 3. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

