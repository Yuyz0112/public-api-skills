# GET /repos/{owner}/{repo}/issues/{issue_number}/events

**Resource:** [issues](../resources/issues.md)
**List issue events**
**Operation ID:** `issues/list-events`

Lists all events for an issue.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 410 | (reference) |

**Success Response Schema:**

Array of [issue-event-for-issue](../schemas/issue-event-for-issue/issue-event-for-issue.md)

