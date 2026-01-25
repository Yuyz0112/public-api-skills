# PUT /rest/api/3/configuration/timetracking

**Resource:** [Time tracking](../resources/Time-tracking.md)
**Select time tracking provider**
**Operation ID:** `selectTimeTrackingImplementation`

Selects a time tracking provider.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [TimeTrackingProvider](../schemas/Time/TimeTrackingProvider.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the time tracking provider is not found. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
