# GET /rest/api/3/workflow

**Resource:** [Workflows](../resources/Workflows.md)
**Get all workflows**
**Operation ID:** `getAllWorkflows`
⚠️ **Deprecated**

This will be removed on [February 1, 2026](https://developer.atlassian.com/cloud/jira/platform/changelog/#CHANGE-2567); use [Search workflows](#api-rest-api-3-workflows-search-get) instead.

Returns all workflows in Jira or a workflow.

If the `workflowName` parameter is specified, the workflow is returned as an object (not in an array). Otherwise, an array of workflow objects is returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowName` | query | string | No | The name of the workflow to be returned. Only one workflow can be specified. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

Array of [DeprecatedWorkflow](../schemas/Deprecated/DeprecatedWorkflow.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
