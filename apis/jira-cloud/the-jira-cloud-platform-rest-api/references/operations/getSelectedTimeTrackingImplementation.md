# GET /rest/api/3/configuration/timetracking

**Resource:** [Time tracking](../resources/Time-tracking.md)
**Get selected time tracking provider**
**Operation ID:** `getSelectedTimeTrackingImplementation`

Returns the time tracking provider that is currently selected. Note that if time tracking is disabled, then a successful but empty response is returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful and time tracking is enabled. |
| 204 | Returned if the request is successful but time tracking is disabled. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[TimeTrackingProvider](../schemas/Time/TimeTrackingProvider.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
