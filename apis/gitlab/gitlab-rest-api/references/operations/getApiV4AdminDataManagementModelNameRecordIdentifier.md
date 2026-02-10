# GET /api/v4/admin/data_management/{model_name}/{record_identifier}

**Resource:** [Data management](../resources/Data-management.md)
**Get data about a specific model**
**Operation ID:** `getApiV4AdminDataManagementModelNameRecordIdentifier`

This feature is experimental.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `model_name` | path | enum: supply_chain_attestations, packages_nuget_symbols, uploads... | Yes |  |
| `record_identifier` | path | any | Yes |  |

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

