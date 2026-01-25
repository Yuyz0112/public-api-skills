# GET /rest/api/3/priority

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Get priorities**
**Operation ID:** `getPriorities`
⚠️ **Deprecated**

Returns the list of all issue priorities.

**[Permissions](#permissions) required:** Permission to access Jira.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

Array of [Priority](../schemas/Priority/Priority.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
