# DELETE /api/v4/admin/ci/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Delete an existing instance-level variable**
**Operation ID:** `deleteApiV4AdminCiVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes | The key of a variable |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 404 | Instance Variable Not Found |

