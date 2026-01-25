# GET /rest/api/3/issuetype/{id}/alternatives

**Resource:** [Issue types](../resources/Issue-types.md)
**Get alternative issue types**
**Operation ID:** `getAlternativeIssueTypes`

Returns a list of issue types that can be used to replace the issue type. The alternative issue types are those assigned to the same workflow scheme, field configuration scheme, and screen scheme.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 404 | Returned if:

 *  the issue type is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

Array of [IssueTypeDetails](../schemas/Issue/IssueTypeDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
