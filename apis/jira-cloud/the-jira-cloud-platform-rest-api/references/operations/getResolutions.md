# GET /rest/api/3/resolution

**Resource:** [Issue resolutions](../resources/Issue-resolutions.md)
**Get resolutions**
**Operation ID:** `getResolutions`
⚠️ **Deprecated**

Returns a list of all issue resolution values.

**[Permissions](#permissions) required:** Permission to access Jira.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [Resolution](../schemas/Resolution/Resolution.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
