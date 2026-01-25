# GET /rest/api/3/securitylevel/{id}

**Resource:** [Issue security level](../resources/Issue-security-level.md)
**Get issue security level**
**Operation ID:** `getIssueSecurityLevel`

Returns details of an issue security level.

Use [Get issue security scheme](#api-rest-api-3-issuesecurityschemes-id-get) to obtain the IDs of issue security levels associated with the issue security scheme.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue security level. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if the issue security level is not found. |

**Success Response Schema:**

[SecurityLevel](../schemas/Security/SecurityLevel.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
