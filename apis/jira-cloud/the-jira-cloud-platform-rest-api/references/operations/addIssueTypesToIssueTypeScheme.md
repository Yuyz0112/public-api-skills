# PUT /rest/api/3/issuetypescheme/{issueTypeSchemeId}/issuetype

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Add issue types to issue type scheme**
**Operation ID:** `addIssueTypesToIssueTypeScheme`

Adds issue types to an issue type scheme.

The added issue types are appended to the issue types list.

If any of the issue types exist in the issue type scheme, the operation fails and no issue types are added.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeSchemeId` | path | integer (int64) | Yes | The ID of the issue type scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeIds](../schemas/Issue/IssueTypeIds.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type or the issue type scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
