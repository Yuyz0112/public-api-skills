# PUT /rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Update issue security level**
**Operation ID:** `updateSecurityLevel`

Updates the issue security level.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | string | Yes | The ID of the issue security scheme level belongs to. |
| `levelId` | path | string | Yes | The ID of the issue security level to update. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateIssueSecurityLevelDetails](../schemas/Update/UpdateIssueSecurityLevelDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue security level isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
