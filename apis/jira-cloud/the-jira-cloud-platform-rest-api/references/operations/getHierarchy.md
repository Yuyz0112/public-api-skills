# GET /rest/api/3/project/{projectId}/hierarchy

**Resource:** [Projects](../resources/Projects.md)
**Get project issue type hierarchy**
**Operation ID:** `getHierarchy`

Get the issue type hierarchy for a next-gen project.

The issue type hierarchy for a project consists of:

 *  *Epic* at level 1 (optional).
 *  One or more issue types at level 0 such as *Story*, *Task*, or *Bug*. Where the issue type *Epic* is defined, these issue types are used to break down the content of an epic.
 *  *Subtask* at level -1 (optional). This issue type enables level 0 issue types to be broken down into components. Issues based on a level -1 issue type must have a parent issue.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | path | integer (int64) | Yes | The ID of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have the necessary permission. |

**Success Response Schema:**

[ProjectIssueTypeHierarchy](../schemas/Project/ProjectIssueTypeHierarchy.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
