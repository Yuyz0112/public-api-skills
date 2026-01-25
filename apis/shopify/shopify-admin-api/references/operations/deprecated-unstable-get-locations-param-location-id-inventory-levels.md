# GET /admin/api/unstable/locations/{location_id}/inventory_levels.json

**Resource:** [inventory/location](../resources/inventory-location.md)
**Retrieves a list of inventory levels for a location. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_unstable_get_locations_param_location_id_inventory_levels`

https://shopify.dev/docs/admin-api/rest/reference/inventory/location#inventory_levels-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `location_id` | path | string | Yes | location_id |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

