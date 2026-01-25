# DELETE /v1/files/{file_key}/dev_resources/{dev_resource_id}

**Resource:** [Dev Resources](../resources/Dev-Resources.md)
**Delete dev resource**
**Operation ID:** `deleteDevResource`

Delete a dev resource from a file

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | The file to delete the dev resource from. This must be a main file key, not a branch key. |
| `dev_resource_id` | path | string | Yes | The id of the dev resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_dev_resources:write
