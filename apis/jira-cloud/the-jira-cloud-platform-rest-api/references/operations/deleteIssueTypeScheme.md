# DELETE /rest/api/3/issuetypescheme/{issueTypeSchemeId}

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Delete issue type scheme**
**Operation ID:** `deleteIssueTypeScheme`

Deletes an issue type scheme.

Only issue type schemes used in classic projects can be deleted.

Any projects assigned to the scheme are reassigned to the default issue type scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeSchemeId` | path | integer (int64) | Yes | The ID of the issue type scheme. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the issue type scheme is deleted. |
| 400 | Returned if the request is to delete the default issue type scheme. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
