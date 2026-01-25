# GET /rest/api/3/workflows/search

**Resource:** [Workflows](../resources/Workflows.md)
**Search workflows**
**Operation ID:** `searchWorkflows`

Returns a [paginated](#pagination) list of global and project workflows. If workflow names are specified in the query string, details of those workflows are returned. Otherwise, all workflows are returned.

**[Permissions](#permissions) required:**

 *  *Administer Jira* global permission to access all, including project-scoped, workflows
 *  At least one of the *Administer projects* and *View (read-only) workflow* project permissions to access project-scoped workflows

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `values.transitions` Returns the transitions that each workflow is associated with. |
| `queryString` | query | string | No | String used to perform a case-insensitive partial match with workflow name. |
| `orderBy` | query | string | No | [Order](#ordering) the results by a field:

 *  `name` Sorts by workflow name.
 *  `created` Sorts by create time.
 *  `updated` Sorts by update time. |
| `scope` | query | string | No | The scope of the workflow. Global for company-managed projects and Project for team-managed projects. |
| `isActive` | query | boolean | No | Filters active and inactive workflows. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[WorkflowSearchResponse](../schemas/Workflow/WorkflowSearchResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
