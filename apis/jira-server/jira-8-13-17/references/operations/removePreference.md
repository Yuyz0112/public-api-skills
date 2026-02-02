# DELETE /mypreferences

**Resource:** [mypreferences](../resources/mypreferences.md)
**Operation ID:** `removePreference`

Removes preference of the currently logged in user. Preference key must be provided as input parameters (key). If
 key parameter is not provided or wrong - status code 404. If preference is unset - status code 204.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | No | - key of the preference to be removed. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

