# WorkflowPayload

The payload for creating workflow, see https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflows/\#api-rest-api-3-workflows-create-post

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the workflow |
| `loopedTransitionContainerLayout` | [WorkflowStatusLayoutPayload](WorkflowStatusLayoutPayload.md) | No |  |
| `name` | string | No | The name of the workflow |
| `onConflict` | enum: FAIL, USE, NEW | No | The strategy to use if there is a conflict with another workflow |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `startPointLayout` | [WorkflowStatusLayoutPayload](WorkflowStatusLayoutPayload.md) | No |  |
| `statuses` | WorkflowStatusPayload[] | No | The statuses to be used in the workflow |
| `transitions` | TransitionPayload[] | No | The transitions for the workflow |

