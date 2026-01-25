# GET /rest/api/3/configuration/timetracking/list

**Resource:** [Time tracking](../resources/Time-tracking.md)
**Get all time tracking providers**
**Operation ID:** `getAvailableTimeTrackingImplementations`

Returns all time tracking providers. By default, Jira only has one time tracking provider: *JIRA provided time tracking*. However, you can install other time tracking providers via apps from the Atlassian Marketplace. For more information on time tracking providers, see the documentation for the [ Time Tracking Provider](https://developer.atlassian.com/cloud/jira/platform/modules/time-tracking-provider/) module.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

Array of [TimeTrackingProvider](../schemas/Time/TimeTrackingProvider.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
