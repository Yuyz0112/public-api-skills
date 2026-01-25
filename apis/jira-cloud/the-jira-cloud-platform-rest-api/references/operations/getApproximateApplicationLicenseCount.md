# GET /rest/api/3/license/approximateLicenseCount/product/{applicationKey}

**Resource:** [License metrics](../resources/License-metrics.md)
**Get approximate application license count**
**Operation ID:** `getApproximateApplicationLicenseCount`

Returns the total approximate number of user accounts for a single Jira license. Note that this information is cached with a 7-day lifecycle and could be stale at the time of call.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `applicationKey` | path | enum: jira-core, jira-product-discovery, jira-software... | Yes | The ID of the application, represents a specific version of Jira. |

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
