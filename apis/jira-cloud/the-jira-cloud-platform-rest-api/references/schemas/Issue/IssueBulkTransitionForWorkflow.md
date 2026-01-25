# IssueBulkTransitionForWorkflow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isTransitionsFiltered` | boolean | No | Indicates whether all the transitions of this workflow are available in the transitions list or not. |
| `issues` | string[] | No | List of issue keys from the request which are associated with this workflow. |
| `transitions` | SimplifiedIssueTransition[] | No | List of transitions available for issues from the request which are associated with this workflow.

 **This list includes only those transitions that are common across the issues in this workflow and do not involve any additional field updates.**  |

