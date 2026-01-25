# OrderOfIssueTypes

An ordered list of issue type IDs and information about where to move them.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string | No | The ID of the issue type to place the moved issue types after. Required if `position` isn't provided. |
| `issueTypeIds` | string[] | Yes | A list of the issue type IDs to move. The order of the issue type IDs in the list is the order they are given after the move. |
| `position` | enum: First, Last | No | The position the issue types should be moved to. Required if `after` isn't provided. |

