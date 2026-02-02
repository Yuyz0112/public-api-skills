# DELETE /user/application

**Resource:** [user](../resources/user.md)
**Operation ID:** `removeUserFromApplication`

Remove user from given application. Admin permission will be required to perform this operation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | username |
| `applicationKey` | query | string | No | application key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

