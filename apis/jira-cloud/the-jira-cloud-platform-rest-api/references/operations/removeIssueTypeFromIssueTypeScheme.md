# DELETE /rest/api/3/issuetypescheme/{issueTypeSchemeId}/issuetype/{issueTypeId}

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Remove issue type from issue type scheme**
**Operation ID:** `removeIssueTypeFromIssueTypeScheme`

Removes an issue type from an issue type scheme.

This operation cannot remove:

 *  any issue type used by issues.
 *  any issue types from the default issue type scheme.
 *  the last standard issue type from an issue type scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeSchemeId` | path | integer (int64) | Yes | The ID of the issue type scheme. |
| `issueTypeId` | path | integer (int64) | Yes | The ID of the issue type. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type scheme is missing or the issue type is not found in the issue type scheme. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
