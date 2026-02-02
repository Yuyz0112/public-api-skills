# PUT /mypreferences

**Resource:** [mypreferences](../resources/mypreferences.md)
**Operation ID:** `setPreference`

Sets preference of the currently logged in user. Preference key must be provided as input parameters (key). Value
 must be provided as post body. If key or value parameter is not provided - status code 404. If preference is set
 - status code 204.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | No | - key of the preference to be set. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

