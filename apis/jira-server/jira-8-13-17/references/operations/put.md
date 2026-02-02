# PUT /applicationrole/{key}

**Resource:** [applicationrole](../resources/applicationrole.md)
**Operation ID:** `put`

Updates the ApplicationRole with the passed data. Only the groups and default groups setting of the
 role may be updated. Requests to change the key or the name of the role will be silently ignored.
 <p>
 Optional: If versionHash is passed through the If-Match header the request will be rejected if not the
 same as server

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `If-Match` | header | string | No | the hash of the version to update. Optional Param |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

