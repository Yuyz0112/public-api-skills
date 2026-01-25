# inventory/inventorylevel

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/inventory_levels.json` | Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-inventory-levels.md) |
| DELETE | `/admin/api/2020-01/inventory_levels.json` | Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level. | [View](../operations/deprecated-202001-delete-inventory-levels.md) |
| POST | `/admin/api/2020-01/inventory_levels/adjust.json` | Adjusts the inventory level of an inventory item at a single location | [View](../operations/deprecated-202001-create-inventory-levels-adjust.md) |
| POST | `/admin/api/2020-01/inventory_levels/connect.json` | Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations. | [View](../operations/deprecated-202001-create-inventory-levels-connect.md) |
| POST | `/admin/api/2020-01/inventory_levels/set.json` | Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations. | [View](../operations/deprecated-202001-create-inventory-levels-set.md) |
| GET | `/admin/api/2020-04/inventory_levels.json` | Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-inventory-levels.md) |
| DELETE | `/admin/api/2020-04/inventory_levels.json` | Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level. | [View](../operations/deprecated-202004-delete-inventory-levels.md) |
| POST | `/admin/api/2020-04/inventory_levels/adjust.json` | Adjusts the inventory level of an inventory item at a single location | [View](../operations/deprecated-202004-create-inventory-levels-adjust.md) |
| POST | `/admin/api/2020-04/inventory_levels/connect.json` | Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations. | [View](../operations/deprecated-202004-create-inventory-levels-connect.md) |
| POST | `/admin/api/2020-04/inventory_levels/set.json` | Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations. | [View](../operations/deprecated-202004-create-inventory-levels-set.md) |
| GET | `/admin/api/2020-07/inventory_levels.json` | Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-inventory-levels.md) |
| DELETE | `/admin/api/2020-07/inventory_levels.json` | Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level. | [View](../operations/deprecated-202007-delete-inventory-levels.md) |
| POST | `/admin/api/2020-07/inventory_levels/adjust.json` | Adjusts the inventory level of an inventory item at a single location | [View](../operations/deprecated-202007-create-inventory-levels-adjust.md) |
| POST | `/admin/api/2020-07/inventory_levels/connect.json` | Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations. | [View](../operations/deprecated-202007-create-inventory-levels-connect.md) |
| POST | `/admin/api/2020-07/inventory_levels/set.json` | Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations. | [View](../operations/deprecated-202007-create-inventory-levels-set.md) |
| GET | `/admin/api/2020-10/inventory_levels.json` | Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-inventory-levels.md) |
| DELETE | `/admin/api/2020-10/inventory_levels.json` | Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level. | [View](../operations/delete-inventory-levels.md) |
| POST | `/admin/api/2020-10/inventory_levels/adjust.json` | Adjusts the inventory level of an inventory item at a single location | [View](../operations/create-inventory-levels-adjust.md) |
| POST | `/admin/api/2020-10/inventory_levels/connect.json` | Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations. | [View](../operations/create-inventory-levels-connect.md) |
| POST | `/admin/api/2020-10/inventory_levels/set.json` | Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations. | [View](../operations/create-inventory-levels-set.md) |
| GET | `/admin/api/2021-01/inventory_levels.json` | Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-inventory-levels.md) |
| DELETE | `/admin/api/2021-01/inventory_levels.json` | Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level. | [View](../operations/deprecated-202101-delete-inventory-levels.md) |
| POST | `/admin/api/2021-01/inventory_levels/adjust.json` | Adjusts the inventory level of an inventory item at a single location | [View](../operations/deprecated-202101-create-inventory-levels-adjust.md) |
| POST | `/admin/api/2021-01/inventory_levels/connect.json` | Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations. | [View](../operations/deprecated-202101-create-inventory-levels-connect.md) |
| POST | `/admin/api/2021-01/inventory_levels/set.json` | Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations. | [View](../operations/deprecated-202101-create-inventory-levels-set.md) |
| GET | `/admin/api/unstable/inventory_levels.json` | Retrieves a list of inventory levels.
          You must include inventory_item_ids, location_ids, or both as filter parameters.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-inventory-levels.md) |
| DELETE | `/admin/api/unstable/inventory_levels.json` | Deletes an inventory level of an inventory item at a location.
          Deleting an inventory level for an inventory item removes that item from the specified location.
          Every inventory item must have at least one inventory level. To move inventory to another location,
          first connect the inventory item to another location, and then delete the previous inventory level. | [View](../operations/deprecated-unstable-delete-inventory-levels.md) |
| POST | `/admin/api/unstable/inventory_levels/adjust.json` | Adjusts the inventory level of an inventory item at a single location | [View](../operations/deprecated-unstable-create-inventory-levels-adjust.md) |
| POST | `/admin/api/unstable/inventory_levels/connect.json` | Connects an inventory item to a location by creating an inventory level at that location.
        When connecting inventory items to locations, it's important to understand the rules around
        fulfillment service locations. | [View](../operations/deprecated-unstable-create-inventory-levels-connect.md) |
| POST | `/admin/api/unstable/inventory_levels/set.json` | Sets the inventory level for an inventory item at a location.
          If the specified location is not connected, it will be automatically connected first.
          When connecting inventory items to locations, it's important to understand the rules around
          fulfillment service locations. | [View](../operations/deprecated-unstable-create-inventory-levels-set.md) |
