# BulkTransitionGetAvailableTransitions

Bulk Transition Get Available Transitions Response.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `availableTransitions` | IssueBulkTransitionForWorkflow[] | No | List of available transitions for bulk transition operation for requested issues grouped by workflow |
| `endingBefore` | string | No | The end cursor for use in pagination. |
| `startingAfter` | string | No | The start cursor for use in pagination. |

