# POST /rest/api/3/issuetype

**Resource:** [Issue types](../resources/Issue-types.md)
**Create issue type**
**Operation ID:** `createIssueType`

Creates an issue type and adds it to the default issue type scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeCreateBean](../schemas/Issue/IssueTypeCreateBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid because:

 *  no content is sent.
 *  the issue type name exceeds 60 characters.
 *  a subtask issue type is requested on an instance where subtasks are disabled. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 409 | Returned if the issue type name is in use. |

**Success Response Schema:**

[IssueTypeDetails](../schemas/Issue/IssueTypeDetails.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
