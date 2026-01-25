# PUT /rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}/member

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Add issue security level members**
**Operation ID:** `addSecurityLevelMembers`

Adds members to the issue security level. You can add up to 100 members per request.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | string | Yes | The ID of the issue security scheme. |
| `levelId` | path | string | Yes | The ID of the issue security level. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SecuritySchemeMembersRequest](../schemas/Security/SecuritySchemeMembersRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the security scheme isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
