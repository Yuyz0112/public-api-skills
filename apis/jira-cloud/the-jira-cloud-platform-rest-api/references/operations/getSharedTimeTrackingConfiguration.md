# GET /rest/api/3/configuration/timetracking/options

**Resource:** [Time tracking](../resources/Time-tracking.md)
**Get time tracking settings**
**Operation ID:** `getSharedTimeTrackingConfiguration`

Returns the time tracking settings. This includes settings such as the time format, default time unit, and others. For more information, see [Configuring time tracking](https://confluence.atlassian.com/x/qoXKM).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[TimeTrackingConfiguration](../schemas/Time/TimeTrackingConfiguration.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
