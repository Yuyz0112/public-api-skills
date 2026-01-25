# GET /repos/{owner}/{repo}/issues/{issue_number}/labels

**Resource:** [issues](../resources/issues.md)
**List labels for an issue**
**Operation ID:** `issues/list-labels-on-issue`

Lists all labels for an issue.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

Array of [label](../schemas/label/label.md)

