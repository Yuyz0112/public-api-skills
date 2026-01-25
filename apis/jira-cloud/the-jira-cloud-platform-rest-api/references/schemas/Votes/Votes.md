# Votes

The details of votes on an issue.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hasVoted` | boolean | No | Whether the user making this request has voted on the issue. |
| `self` | string (uri) | No | The URL of these issue vote details. |
| `voters` | User[] | No | List of the users who have voted on this issue. An empty list is returned when the calling user doesn't have the *View voters and watchers* project permission. |
| `votes` | integer (int64) | No | The number of votes on the issue. |

