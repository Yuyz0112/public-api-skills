# DELETE /rest/api/3/issuesecurityschemes/{schemeId}

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Delete issue security scheme**
**Operation ID:** `deleteSecurityScheme`

Deletes an issue security scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | string | Yes | The ID of the issue security scheme. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue security scheme isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
