# GET /api/v4/offline_exports

**Resource:** [offline_exports](../resources/offline-exports.md)
**List all offline transfer exports**
**Operation ID:** `getApiV4OfflineExports`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `sort` | query | enum: asc, desc | No | Return offline transfer exports sorted in created by `asc` or `desc` order. |
| `status` | query | enum: created, started, finished... | No | Return offline transfer exports with specified status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

