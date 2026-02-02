# DELETE /role/{id}/actors

**Resource:** [role](../resources/role.md)
**Operation ID:** `deleteProjectRoleActorsFromRole`

Removes default actor from the given role.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user` | query | string | No | if given, removes an actor from given role |
| `group` | query | string | No | if given, removes an actor from given role |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

