# GET /mypreferences

**Resource:** [mypreferences](../resources/mypreferences.md)
**Operation ID:** `getPreference`

Returns preference of the currently logged in user. Preference key must be provided as input parameter (key). The
 value is returned exactly as it is. If key parameter is not provided or wrong - status code 404. If value is
 found  - status code 200.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | No | - key of the preference to be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

