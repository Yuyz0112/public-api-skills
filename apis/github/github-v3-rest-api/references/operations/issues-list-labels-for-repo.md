# GET /repos/{owner}/{repo}/labels

**Resource:** [issues](../resources/issues.md)
**List labels for a repository**
**Operation ID:** `issues/list-labels-for-repo`

Lists all labels for a repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [label](../schemas/label/label.md)

