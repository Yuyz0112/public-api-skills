# GET /rest/api/3/workflow/search

**Resource:** [Workflows](../resources/Workflows.md)
**Get workflows paginated**
**Operation ID:** `getWorkflowsPaginated`
⚠️ **Deprecated**

This will be removed on [June 1, 2026](https://developer.atlassian.com/cloud/jira/platform/changelog/#CHANGE-2569); use [Search workflows](#api-rest-api-3-workflows-search-get) instead.

Returns a [paginated](#pagination) list of published classic workflows. When workflow names are specified, details of those workflows are returned. Otherwise, all published classic workflows are returned.

This operation does not return next-gen workflows.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `workflowName` | query | string[] | No | The name of a workflow to return. To include multiple workflows, provide an ampersand-separated list. For example, `workflowName=name1&workflowName=name2`. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `transitions` For each workflow, returns information about the transitions inside the workflow.
 *  `transitions.rules` For each workflow transition, returns information about its rules. Transitions are included automatically if this expand is requested.
 *  `transitions.properties` For each workflow transition, returns information about its properties. Transitions are included automatically if this expand is requested.
 *  `statuses` For each workflow, returns information about the statuses inside the workflow.
 *  `statuses.properties` For each workflow status, returns information about its properties. Statuses are included automatically if this expand is requested.
 *  `default` For each workflow, returns information about whether this is the default workflow.
 *  `schemes` For each workflow, returns information about the workflow schemes the workflow is assigned to.
 *  `projects` For each workflow, returns information about the projects the workflow is assigned to, through workflow schemes.
 *  `hasDraftWorkflow` For each workflow, returns information about whether the workflow has a draft version.
 *  `operations` For each workflow, returns information about the actions that can be undertaken on the workflow. |
| `queryString` | query | string | No | String used to perform a case-insensitive partial match with workflow name. |
| `orderBy` | query | enum: name, -name, +name... | No | [Order](#ordering) the results by a field:

 *  `name` Sorts by workflow name.
 *  `created` Sorts by create time.
 *  `updated` Sorts by update time. |
| `isActive` | query | boolean | No | Filters active and inactive workflows. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanWorkflow](../schemas/Page/PageBeanWorkflow.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
