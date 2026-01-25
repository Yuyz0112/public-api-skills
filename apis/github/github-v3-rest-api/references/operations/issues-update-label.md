# PATCH /repos/{owner}/{repo}/labels/{name}

**Resource:** [issues](../resources/issues.md)
**Update a label**
**Operation ID:** `issues/update-label`

Updates a label using the given label name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[label](../schemas/label/label.md)

