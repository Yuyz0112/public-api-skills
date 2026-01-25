# GET /rest/api/3/license/approximateLicenseCount

**Resource:** [License metrics](../resources/License-metrics.md)
**Get approximate license count**
**Operation ID:** `getApproximateLicenseCount`

Returns the approximate number of user accounts across all Jira licenses. Note that this information is cached with a 7-day lifecycle and could be stale at the time of call.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to complete this request. |

**Success Response Schema:**

[LicenseMetric](../schemas/License/LicenseMetric.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
