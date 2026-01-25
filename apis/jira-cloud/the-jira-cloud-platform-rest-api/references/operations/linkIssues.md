# POST /rest/api/3/issueLink

**Resource:** [Issue links](../resources/Issue-links.md)
**Create issue link**
**Operation ID:** `linkIssues`

Creates a link between two issues. Use this operation to indicate a relationship between two issues and optionally add a comment to the from (outward) issue. To use this resource the site must have [Issue Linking](https://confluence.atlassian.com/x/yoXKM) enabled.

This resource returns nothing on the creation of an issue link. To obtain the ID of the issue link, use `https://your-domain.atlassian.net/rest/api/3/issue/[linked issue key]?fields=issuelinks`.

If the link request duplicates a link, the response indicates that the issue link was created. If the request included a comment, the comment is added.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse project* [project permission](https://confluence.atlassian.com/x/yodKLg) for all the projects containing the issues to be linked,
 *  *Link issues* [project permission](https://confluence.atlassian.com/x/yodKLg) on the project containing the from (outward) issue,
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If the comment has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Request Body

The issue link request.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [LinkIssueRequestJsonBean](../schemas/Link/LinkIssueRequestJsonBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the comment is not created. The response contains an error message indicating why the comment wasn't created. The issue link is also not created. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  issue linking is disabled.
 *  the user cannot view one or both of the issues. For example, the user doesn't have *Browse project* project permission for a project containing one of the issues.
 *  the user does not have *link issues* project permission.
 *  either of the link issues are not found.
 *  the issue link type is not found. |
| 413 | Returned if the per-issue limit for issue links has been breached. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
