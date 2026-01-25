# GET /rest/api/3/configuration

**Resource:** [Jira settings](../resources/Jira-settings.md)
**Get global settings**
**Operation ID:** `getConfiguration`

Returns the [global settings](https://confluence.atlassian.com/x/qYXKM) in Jira. These settings determine whether optional features (for example, subtasks, time tracking, and others) are enabled. If time tracking is enabled, this operation also returns the time tracking configuration.

**[Permissions](#permissions) required:** Permission to access Jira.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[Configuration](../schemas/Configuration/Configuration.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
