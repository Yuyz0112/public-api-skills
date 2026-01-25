# POST /rest/api/3/issue/bulk

**Resource:** [Issues](../resources/Issues.md)
**Bulk create issue**
**Operation ID:** `createIssues`

Creates upto **50** issues and, where the option to create subtasks is enabled in Jira, subtasks. Transitions may be applied, to move the issues or subtasks to a workflow step other than the default start step, and issue properties set.

The content of each issue or subtask is defined using `update` and `fields`. The fields that can be set in the issue or subtask are determined using the [ Get create issue metadata](#api-rest-api-3-issue-createmeta-get). These are the same fields that appear on the issues' create screens. Note that the `description`, `environment`, and any `textarea` type custom fields (multi-line text fields) take Atlassian Document Format content. Single line custom fields (`textfield`) accept a string and don't handle Atlassian Document Format content.

Creating a subtask differs from creating an issue as follows:

 *  `issueType` must be set to a subtask issue type (use [ Get create issue metadata](#api-rest-api-3-issue-createmeta-get) to find subtask issue types).
 *  `parent` the must contain the ID or key of the parent issue.

**[Permissions](#permissions) required:** *Browse projects* and *Create issues* [project permissions](https://confluence.atlassian.com/x/yodKLg) for the project in which each issue or subtask is created.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssuesUpdateBean](../schemas/Issues/IssuesUpdateBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if any of the issue or subtask creation requests were successful. A request may be unsuccessful when it:

 *  is missing required fields.
 *  contains invalid field values.
 *  contains fields that cannot be set for the issue type.
 *  is by a user who does not have the necessary permission.
 *  is to create a subtype in a project different that of the parent issue.
 *  is for a subtask when the option to create subtasks is disabled.
 *  is invalid for any other reason. |
| 400 | Returned if all requests are invalid. Requests may be unsuccessful when they:

 *  are missing required fields.
 *  contain invalid field values.
 *  contain fields that cannot be set for the issue type.
 *  are by a user who does not have the necessary permission.
 *  are to create a subtype in a project different that of the parent issue.
 *  is for a subtask when the option to create subtasks is disabled.
 *  are invalid for any other reason. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[CreatedIssues](../schemas/Created/CreatedIssues.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
