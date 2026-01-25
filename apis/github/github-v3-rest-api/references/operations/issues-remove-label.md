# DELETE /repos/{owner}/{repo}/issues/{issue_number}/labels/{name}

**Resource:** [issues](../resources/issues.md)
**Remove a label from an issue**
**Operation ID:** `issues/remove-label`

Removes the specified label from the issue, and returns the remaining labels on the issue. This endpoint returns a `404 Not Found` status if the label does not exist.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

Array of [label](../schemas/label/label.md)

