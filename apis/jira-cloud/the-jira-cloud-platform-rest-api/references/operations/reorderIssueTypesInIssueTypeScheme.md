# PUT /rest/api/3/issuetypescheme/{issueTypeSchemeId}/issuetype/move

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Change order of issue types**
**Operation ID:** `reorderIssueTypesInIssueTypeScheme`

Changes the order of issue types in an issue type scheme.

The request body parameters must meet the following requirements:

 *  all of the issue types must belong to the issue type scheme.
 *  either `after` or `position` must be provided.
 *  the issue type in `after` must not be in the issue type list.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeSchemeId` | path | integer (int64) | Yes | The ID of the issue type scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [OrderOfIssueTypes](../schemas/Order/OrderOfIssueTypes.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
