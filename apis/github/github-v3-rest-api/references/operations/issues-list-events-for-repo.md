# GET /repos/{owner}/{repo}/issues/events

**Resource:** [issues](../resources/issues.md)
**List issue events for a repository**
**Operation ID:** `issues/list-events-for-repo`

Lists events for a repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

Array of [issue-event](../schemas/issue-event/issue-event.md)

