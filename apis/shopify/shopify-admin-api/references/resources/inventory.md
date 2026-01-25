# inventory

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/inventory_items.json` | Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-inventory-items.md) |
| GET | `/admin/api/2020-01/inventory_items/{inventory_item_id}.json` | Retrieves a single inventory item by ID | [View](../operations/deprecated-202001-get-inventory-items-param-inventory-item-id.md) |
| PUT | `/admin/api/2020-01/inventory_items/{inventory_item_id}.json` | Updates an existing inventory item | [View](../operations/deprecated-202001-update-inventory-items-param-inventory-item-id.md) |
| GET | `/admin/api/2020-04/inventory_items.json` | Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-inventory-items.md) |
| GET | `/admin/api/2020-04/inventory_items/{inventory_item_id}.json` | Retrieves a single inventory item by ID | [View](../operations/deprecated-202004-get-inventory-items-param-inventory-item-id.md) |
| PUT | `/admin/api/2020-04/inventory_items/{inventory_item_id}.json` | Updates an existing inventory item | [View](../operations/deprecated-202004-update-inventory-items-param-inventory-item-id.md) |
| GET | `/admin/api/2020-07/inventory_items.json` | Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-inventory-items.md) |
| GET | `/admin/api/2020-07/inventory_items/{inventory_item_id}.json` | Retrieves a single inventory item by ID | [View](../operations/deprecated-202007-get-inventory-items-param-inventory-item-id.md) |
| PUT | `/admin/api/2020-07/inventory_items/{inventory_item_id}.json` | Updates an existing inventory item | [View](../operations/deprecated-202007-update-inventory-items-param-inventory-item-id.md) |
| GET | `/admin/api/2020-10/inventory_items.json` | Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-inventory-items.md) |
| GET | `/admin/api/2020-10/inventory_items/{inventory_item_id}.json` | Retrieves a single inventory item by ID | [View](../operations/get-inventory-items-param-inventory-item-id.md) |
| PUT | `/admin/api/2020-10/inventory_items/{inventory_item_id}.json` | Updates an existing inventory item | [View](../operations/update-inventory-items-param-inventory-item-id.md) |
| GET | `/admin/api/2021-01/inventory_items.json` | Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-inventory-items.md) |
| GET | `/admin/api/2021-01/inventory_items/{inventory_item_id}.json` | Retrieves a single inventory item by ID | [View](../operations/deprecated-202101-get-inventory-items-param-inventory-item-id.md) |
| PUT | `/admin/api/2021-01/inventory_items/{inventory_item_id}.json` | Updates an existing inventory item | [View](../operations/deprecated-202101-update-inventory-items-param-inventory-item-id.md) |
| GET | `/admin/api/unstable/inventory_items.json` | Retrieves a list of inventory items. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-inventory-items.md) |
| GET | `/admin/api/unstable/inventory_items/{inventory_item_id}.json` | Retrieves a single inventory item by ID | [View](../operations/deprecated-unstable-get-inventory-items-param-inventory-item-id.md) |
| PUT | `/admin/api/unstable/inventory_items/{inventory_item_id}.json` | Updates an existing inventory item | [View](../operations/deprecated-unstable-update-inventory-items-param-inventory-item-id.md) |
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
| GET | `/admin/api/2020-01/locations.json` | Retrieves a list of locations | [View](../operations/deprecated-202001-get-locations.md) |
| GET | `/admin/api/2020-01/locations/{location_id}.json` | Retrieves a single location by its ID | [View](../operations/deprecated-202001-get-locations-param-location-id.md) |
| GET | `/admin/api/2020-01/locations/count.json` | Retrieves a count of locations | [View](../operations/deprecated-202001-get-locations-count.md) |
| GET | `/admin/api/2020-01/locations/{location_id}/inventory_levels.json` | Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-locations-param-location-id-inventory-levels.md) |
| GET | `/admin/api/2020-04/locations.json` | Retrieves a list of locations | [View](../operations/deprecated-202004-get-locations.md) |
| GET | `/admin/api/2020-04/locations/{location_id}.json` | Retrieves a single location by its ID | [View](../operations/deprecated-202004-get-locations-param-location-id.md) |
| GET | `/admin/api/2020-04/locations/count.json` | Retrieves a count of locations | [View](../operations/deprecated-202004-get-locations-count.md) |
| GET | `/admin/api/2020-04/locations/{location_id}/inventory_levels.json` | Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-locations-param-location-id-inventory-levels.md) |
| GET | `/admin/api/2020-07/locations.json` | Retrieves a list of locations | [View](../operations/deprecated-202007-get-locations.md) |
| GET | `/admin/api/2020-07/locations/{location_id}.json` | Retrieves a single location by its ID | [View](../operations/deprecated-202007-get-locations-param-location-id.md) |
| GET | `/admin/api/2020-07/locations/count.json` | Retrieves a count of locations | [View](../operations/deprecated-202007-get-locations-count.md) |
| GET | `/admin/api/2020-07/locations/{location_id}/inventory_levels.json` | Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-locations-param-location-id-inventory-levels.md) |
| GET | `/admin/api/2020-10/locations.json` | Retrieves a list of locations | [View](../operations/get-locations.md) |
| GET | `/admin/api/2020-10/locations/{location_id}.json` | Retrieves a single location by its ID | [View](../operations/get-locations-param-location-id.md) |
| GET | `/admin/api/2020-10/locations/count.json` | Retrieves a count of locations | [View](../operations/get-locations-count.md) |
| GET | `/admin/api/2020-10/locations/{location_id}/inventory_levels.json` | Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-locations-param-location-id-inventory-levels.md) |
| GET | `/admin/api/2021-01/locations.json` | Retrieves a list of locations | [View](../operations/deprecated-202101-get-locations.md) |
| GET | `/admin/api/2021-01/locations/{location_id}.json` | Retrieves a single location by its ID | [View](../operations/deprecated-202101-get-locations-param-location-id.md) |
| GET | `/admin/api/2021-01/locations/count.json` | Retrieves a count of locations | [View](../operations/deprecated-202101-get-locations-count.md) |
| GET | `/admin/api/2021-01/locations/{location_id}/inventory_levels.json` | Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-locations-param-location-id-inventory-levels.md) |
| GET | `/admin/api/unstable/locations.json` | Retrieves a list of locations | [View](../operations/deprecated-unstable-get-locations.md) |
| GET | `/admin/api/unstable/locations/{location_id}.json` | Retrieves a single location by its ID | [View](../operations/deprecated-unstable-get-locations-param-location-id.md) |
| GET | `/admin/api/unstable/locations/count.json` | Retrieves a count of locations | [View](../operations/deprecated-unstable-get-locations-count.md) |
| GET | `/admin/api/unstable/locations/{location_id}/inventory_levels.json` | Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-locations-param-location-id-inventory-levels.md) |
