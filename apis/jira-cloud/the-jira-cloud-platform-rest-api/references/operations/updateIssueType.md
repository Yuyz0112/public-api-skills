# PUT /rest/api/3/issuetype/{id}

**Resource:** [Issue types](../resources/Issue-types.md)
**Update issue type**
**Operation ID:** `updateIssueType`

Updates the issue type.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue type. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeUpdateBean](../schemas/Issue/IssueTypeUpdateBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid because:

 *  no content is sent.
 *  the issue type name exceeds 60 characters.
 *  the avatar is not associated with this issue type. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the issue type is not found. |
| 409 | Returned if the issue type name is in use. |

**Success Response Schema:**

[IssueTypeDetails](../schemas/Issue/IssueTypeDetails.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
