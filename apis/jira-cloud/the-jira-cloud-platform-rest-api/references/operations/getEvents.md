# GET /rest/api/3/events

**Resource:** [Issues](../resources/Issues.md)
**Get events**
**Operation ID:** `getEvents`

Returns all issue events.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to complete this request. |

**Success Response Schema:**

Array of [IssueEvent](../schemas/Issue/IssueEvent.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
