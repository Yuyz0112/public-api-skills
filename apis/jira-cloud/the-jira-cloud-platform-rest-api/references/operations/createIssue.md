# POST /rest/api/3/issue

**Resource:** [Issues](../resources/Issues.md)
**Create issue**
**Operation ID:** `createIssue`

Creates an issue or, where the option to create subtasks is enabled in Jira, a subtask. A transition may be applied, to move the issue or subtask to a workflow step other than the default start step, and issue properties set.

The content of the issue or subtask is defined using `update` and `fields`. The fields that can be set in the issue or subtask are determined using the [ Get create issue metadata](#api-rest-api-3-issue-createmeta-get). These are the same fields that appear on the issue's create screen. Note that the `description`, `environment`, and any `textarea` type custom fields (multi-line text fields) take Atlassian Document Format content. Single line custom fields (`textfield`) accept a string and don't handle Atlassian Document Format content.

Creating a subtask differs from creating an issue as follows:

 *  `issueType` must be set to a subtask issue type (use [ Get create issue metadata](#api-rest-api-3-issue-createmeta-get) to find subtask issue types).
 *  `parent` must contain the ID or key of the parent issue.

In a next-gen project any issue may be made a child providing that the parent and child are members of the same project.

**[Permissions](#permissions) required:** *Browse projects* and *Create issues* [project permissions](https://confluence.atlassian.com/x/yodKLg) for the project in which the issue or subtask is created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `updateHistory` | query | boolean | No | Whether the project in which the issue is created is added to the user's **Recently viewed** project list, as shown under **Projects** in Jira. When provided, the issue type and request type are added to the user's history for a project. These values are then used to provide defaults on the issue create screen. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueUpdateDetails](../schemas/Issue/IssueUpdateDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request:

 *  is missing required fields.
 *  contains invalid field values.
 *  contains fields that cannot be set for the issue type.
 *  is by a user who does not have the necessary permission.
 *  is to create a subtype in a project different that of the parent issue.
 *  is for a subtask when the option to create subtasks is disabled.
 *  is invalid for any other reason. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 422 | Returned if a configuration problem prevents the creation of the issue. |

**Success Response Schema:**

[CreatedIssue](../schemas/Created/CreatedIssue.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
