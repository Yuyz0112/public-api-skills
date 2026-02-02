# PUT /applicationrole

**Resource:** [applicationrole](../resources/applicationrole.md)
**Operation ID:** `putBulk`

Updates the ApplicationRoles with the passed data if the version hash is the same as the server.
 Only the groups and default groups setting of the role may be updated. Requests to change the key
 or the name of the role will be silently ignored. It is acceptable to pass only the roles that are updated
 as roles that are present in the server but not in data to update with, will not be deleted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `If-Match` | header | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

