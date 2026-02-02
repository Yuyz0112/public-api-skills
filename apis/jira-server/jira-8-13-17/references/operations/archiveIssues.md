# POST /issue/archive

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `archiveIssues`

Archives a list of issues.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `notifyUsers` | query | boolean | No | send the email with notification that the issue was updated to users that watch it.
                    Admin or project admin permissions are required to disable the notification. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

