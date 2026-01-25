# DELETE /rest/api/3/workflow/transitions/{transitionId}/properties

**Resource:** [Workflow transition properties](../resources/Workflow-transition-properties.md)
**Delete workflow transition property**
**Operation ID:** `deleteWorkflowTransitionProperty`
⚠️ **Deprecated**

This will be removed on [June 1, 2026](https://developer.atlassian.com/cloud/jira/platform/changelog/#CHANGE-2570); delete transition properties using [Bulk update workflows](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflows/#api-rest-api-3-workflows-update-post) instead.

Deletes a property from a workflow transition. Transition properties are used to change the behavior of a transition. For more information, see [Transition properties](https://confluence.atlassian.com/x/zIhKLg#Advancedworkflowconfiguration-transitionproperties) and [Workflow properties](https://confluence.atlassian.com/x/JYlKLg).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `transitionId` | path | integer (int64) | Yes | The ID of the transition. To get the ID, view the workflow in text mode in the Jira admin settings. The ID is shown next to the transition. |
| `key` | query | string | Yes | The name of the transition property to delete, also known as the name of the property. |
| `workflowName` | query | string | Yes | The name of the workflow that the transition belongs to. |
| `workflowMode` | query | enum: live, draft | No | The workflow status. Set to `live` for inactive workflows or `draft` for draft workflows. Active workflows cannot be edited. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response |
| 304 | Returned if no changes were made by the request. For example, trying to delete a property that cannot be found. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the workflow transition is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
