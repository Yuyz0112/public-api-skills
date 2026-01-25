# POST /repos/{owner}/{repo}/issues/{issue_number}/labels

**Resource:** [issues](../resources/issues.md)
**Add labels to an issue**
**Operation ID:** `issues/add-labels`

Adds labels to an issue. If you provide an empty array of labels, all labels are removed from the issue. 

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

