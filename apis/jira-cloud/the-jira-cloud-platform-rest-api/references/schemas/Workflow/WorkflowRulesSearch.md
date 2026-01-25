# WorkflowRulesSearch

Details of the workflow and its transition rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expand` | string | No | Use expand to include additional information in the response. This parameter accepts `transition` which, for each rule, returns information about the transition the rule is assigned to. |
| `ruleIds` | string[] | Yes | The list of workflow rule IDs. |
| `workflowEntityId` | string (uuid) | Yes | The workflow ID. |

