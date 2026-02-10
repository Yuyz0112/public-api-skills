# GET /api/v4/admin/data_management/{model_name}

**Resource:** [Data management](../resources/Data-management.md)
**Get a list of model data**
**Operation ID:** `getApiV4AdminDataManagementModelName`

This feature is experimental.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `model_name` | path | enum: supply_chain_attestations, packages_nuget_symbols, uploads... | Yes |  |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `identifiers` | query | any | No | The record identifiers to filter by |
| `checksum_state` | query | enum: pending, started, succeeded... | No | The checksum status of the records to filter by |
| `cursor` | query | string | No | Cursor for obtaining the next set of records |
| `sort` | query | enum: asc, desc | No | Order of sorting |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Model Not Found |

**Success Response Schema:**

[APIEntitiesAdminModel](../schemas/APIEntitiesAdminModel/APIEntitiesAdminModel.md)

