# PUT /repos/{owner}/{repo}/issues/{issue_number}/labels

**Resource:** [issues](../resources/issues.md)
**Set labels for an issue**
**Operation ID:** `issues/set-labels`

Removes any previous labels and sets the new labels for an issue.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 404 | (reference) |
| 410 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [label](../schemas/label/label.md)

