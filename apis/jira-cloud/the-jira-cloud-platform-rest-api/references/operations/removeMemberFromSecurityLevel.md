# DELETE /rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}/member/{memberId}

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Remove member from issue security level**
**Operation ID:** `removeMemberFromSecurityLevel`

Removes an issue security level member from an issue security scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | string | Yes | The ID of the issue security scheme. |
| `levelId` | path | string | Yes | The ID of the issue security level. |
| `memberId` | path | string | Yes | The ID of the issue security level member to be removed. |

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
