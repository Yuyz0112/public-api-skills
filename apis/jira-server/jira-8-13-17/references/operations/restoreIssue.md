# PUT /issue/{issueIdOrKey}/restore

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `restoreIssue`

Restores an archived issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `notifyUsers` | query | boolean | No | send the email with notification that the issue was updated to users that watch it.
                     Admin or project admin permissions are required to disable the notification. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

