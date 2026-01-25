# PUT /rest/api/3/configuration/timetracking/options

**Resource:** [Time tracking](../resources/Time-tracking.md)
**Set time tracking settings**
**Operation ID:** `setSharedTimeTrackingConfiguration`

Sets the time tracking settings.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [TimeTrackingConfiguration](../schemas/Time/TimeTrackingConfiguration.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request object is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[TimeTrackingConfiguration](../schemas/Time/TimeTrackingConfiguration.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
