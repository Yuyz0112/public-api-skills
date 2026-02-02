# DELETE /issue/{issueIdOrKey}/watchers

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `removeWatcher`

Removes a user from an issue's watcher list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | a String containing the name of the user to remove from the watcher list. Must not be null. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

