# GET /rest/api/3/instance/license

**Resource:** [License metrics](../resources/License-metrics.md)
**Get license**
**Operation ID:** `getLicense`

Returns licensing information about the Jira instance.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[License](../schemas/License/License.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
