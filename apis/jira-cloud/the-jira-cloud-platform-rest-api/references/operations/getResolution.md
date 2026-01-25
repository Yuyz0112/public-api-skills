# GET /rest/api/3/resolution/{id}

**Resource:** [Issue resolutions](../resources/Issue-resolutions.md)
**Get resolution**
**Operation ID:** `getResolution`

Returns an issue resolution value.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue resolution value. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the issue resolution value is not found. |

**Success Response Schema:**

[Resolution](../schemas/Resolution/Resolution.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
