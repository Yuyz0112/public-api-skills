# DELETE /role/{id}

**Resource:** [role](../resources/role.md)
**Operation ID:** `deleteProjectRole`

Deletes a role. May return 403 in the future

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `swap` | query | integer (int64) | No | if given, removes a role even if it is used in scheme by replacing the role with the given one |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

