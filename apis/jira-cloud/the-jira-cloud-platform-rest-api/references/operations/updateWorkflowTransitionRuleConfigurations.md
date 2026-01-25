# PUT /rest/api/3/workflow/rule/config

**Resource:** [Workflow transition rules](../resources/Workflow-transition-rules.md)
**Update workflow transition rule configurations**
**Operation ID:** `updateWorkflowTransitionRuleConfigurations`

Updates configuration of workflow transition rules. The following rule types are supported:

 *  [post functions](https://developer.atlassian.com/cloud/jira/platform/modules/workflow-post-function/)
 *  [conditions](https://developer.atlassian.com/cloud/jira/platform/modules/workflow-condition/)
 *  [validators](https://developer.atlassian.com/cloud/jira/platform/modules/workflow-validator/)

Only rules created by the calling [Connect](https://developer.atlassian.com/cloud/jira/platform/index/#connect-apps) or [Forge](https://developer.atlassian.com/cloud/jira/platform/index/#forge-apps) app can be updated.

To assist with app migration, this operation can be used to:

 *  Disable a rule.
 *  Add a `tag`. Use this to filter rules in the [Get workflow transition rule configurations](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-transition-rules/#api-rest-api-3-workflow-rule-config-get).

Rules are enabled if the `disabled` parameter is not provided.

**[Permissions](#permissions) required:** Only [Connect](https://developer.atlassian.com/cloud/jira/platform/index/#connect-apps) or [Forge](https://developer.atlassian.com/cloud/jira/platform/index/#forge-apps) apps can use this operation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowTransitionRulesUpdate](../schemas/Workflow/WorkflowTransitionRulesUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the caller is not a Connect or Forge app. |
| 503 | Returned if we encounter a problem while trying to access the required data. |

**Success Response Schema:**

[WorkflowTransitionRulesUpdateErrors](../schemas/Workflow/WorkflowTransitionRulesUpdateErrors.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
