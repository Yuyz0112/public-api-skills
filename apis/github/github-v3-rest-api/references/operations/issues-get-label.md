# GET /repos/{owner}/{repo}/labels/{name}

**Resource:** [issues](../resources/issues.md)
**Get a label**
**Operation ID:** `issues/get-label`

Gets a label using the given name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[label](../schemas/label/label.md)

