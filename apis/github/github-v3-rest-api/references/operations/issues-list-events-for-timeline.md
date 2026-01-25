# GET /repos/{owner}/{repo}/issues/{issue_number}/timeline

**Resource:** [issues](../resources/issues.md)
**List timeline events for an issue**
**Operation ID:** `issues/list-events-for-timeline`

List all timeline events for an issue.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

Array of [timeline-issue-events](../schemas/timeline-issue-events/timeline-issue-events.md)

