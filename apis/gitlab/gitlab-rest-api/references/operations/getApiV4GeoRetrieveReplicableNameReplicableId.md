# GET /api/v4/geo/retrieve/{replicable_name}/{replicable_id}

**Resource:** [Geo](../resources/Geo.md)
**Returns a replicable file from store (via CDN or sendfile)**
**Operation ID:** `getApiV4GeoRetrieveReplicableNameReplicableId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `replicable_name` | path | string | Yes | The replicable name of a replicator instance |
| `replicable_id` | path | integer | Yes | The replicable ID of a replicable instance |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 Not found |

