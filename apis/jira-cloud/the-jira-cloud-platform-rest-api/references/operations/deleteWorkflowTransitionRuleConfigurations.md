# PUT /rest/api/3/workflow/rule/config/delete

**Resource:** [Workflow transition rules](../resources/Workflow-transition-rules.md)
**Delete workflow transition rule configurations**
**Operation ID:** `deleteWorkflowTransitionRuleConfigurations`

Deletes workflow transition rules from one or more workflows. These rule types are supported:

 *  [post functions](https://developer.atlassian.com/cloud/jira/platform/modules/workflow-post-function/)
 *  [conditions](https://developer.atlassian.com/cloud/jira/platform/modules/workflow-condition/)
 *  [validators](https://developer.atlassian.com/cloud/jira/platform/modules/workflow-validator/)

Only rules created by the calling Connect app can be deleted.

**[Permissions](#permissions) required:** Only Connect apps can use this operation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowsWithTransitionRulesDetails](../schemas/Workflows/WorkflowsWithTransitionRulesDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the caller is not a Connect app. |

**Success Response Schema:**

[WorkflowTransitionRulesUpdateErrors](../schemas/Workflow/WorkflowTransitionRulesUpdateErrors.md)

## Security

- **basicAuth**
