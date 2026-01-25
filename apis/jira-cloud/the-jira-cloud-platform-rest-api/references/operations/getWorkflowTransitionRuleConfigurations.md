# GET /rest/api/3/workflow/rule/config

**Resource:** [Workflow transition rules](../resources/Workflow-transition-rules.md)
**Get workflow transition rule configurations**
**Operation ID:** `getWorkflowTransitionRuleConfigurations`

Returns a [paginated](#pagination) list of workflows with transition rules. The workflows can be filtered to return only those containing workflow transition rules:

 *  of one or more transition rule types, such as [workflow post functions](https://developer.atlassian.com/cloud/jira/platform/modules/workflow-post-function/).
 *  matching one or more transition rule keys.

Only workflows containing transition rules created by the calling [Connect](https://developer.atlassian.com/cloud/jira/platform/index/#connect-apps) or [Forge](https://developer.atlassian.com/cloud/jira/platform/index/#forge-apps) app are returned.

Due to server-side optimizations, workflows with an empty list of rules may be returned; these workflows can be ignored.

**[Permissions](#permissions) required:** Only [Connect](https://developer.atlassian.com/cloud/jira/platform/index/#connect-apps) or [Forge](https://developer.atlassian.com/cloud/jira/platform/index/#forge-apps) apps can use this operation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `types` | query | string[] | Yes | The types of the transition rules to return. |
| `keys` | query | string[] | No | The transition rule class keys, as defined in the Connect or the Forge app descriptor, of the transition rules to return. |
| `workflowNames` | query | string[] | No | The list of workflow names to filter by. |
| `withTags` | query | string[] | No | The list of `tags` to filter by. |
| `draft` | query | boolean | No | Whether draft or published workflows are returned. If not provided, both workflow types are returned. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts `transition`, which, for each rule, returns information about the transition the rule is assigned to. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the caller is not a Connect or Forge app. |
| 404 | Returned if any transition rule type is not supported. |
| 503 | Returned if we encounter a problem while trying to access the required data. |

**Success Response Schema:**

[PageBeanWorkflowTransitionRules](../schemas/Page/PageBeanWorkflowTransitionRules.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
