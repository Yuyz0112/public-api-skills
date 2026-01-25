# GET /rest/api/3/issuetype/{id}

**Resource:** [Issue types](../resources/Issue-types.md)
**Get issue type**
**Operation ID:** `getIssueType`

Returns an issue type.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) in a project the issue type is associated with or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the issue type ID is invalid. |
| 404 | Returned if:

 *  the issue type is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[IssueTypeDetails](../schemas/Issue/IssueTypeDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
