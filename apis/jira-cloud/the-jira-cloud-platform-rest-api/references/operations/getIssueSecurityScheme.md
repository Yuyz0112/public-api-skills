# GET /rest/api/3/issuesecurityschemes/{id}

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Get issue security scheme**
**Operation ID:** `getIssueSecurityScheme`

Returns an issue security scheme along with its security levels.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for a project that uses the requested issue security scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the issue security scheme. Use the [Get issue security schemes](#api-rest-api-3-issuesecurityschemes-get) operation to get a list of issue security scheme IDs. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the administrator permission and the scheme is not used in any project where the user has administrative permission. |

**Success Response Schema:**

[SecurityScheme](../schemas/Security/SecurityScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
