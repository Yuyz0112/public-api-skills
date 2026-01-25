# GET /rest/api/3/priority/{id}

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Get priority**
**Operation ID:** `getPriority`

Returns an issue priority.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue priority. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if the issue priority isn't found. |

**Success Response Schema:**

[Priority](../schemas/Priority/Priority.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
