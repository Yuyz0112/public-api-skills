# POST /repos/{owner}/{repo}/labels

**Resource:** [issues](../resources/issues.md)
**Create a label**
**Operation ID:** `issues/create-label`

Creates a label for the specified repository with the given name and color. The name and color parameters are required. The color must be a valid [hexadecimal color code](http://www.color-hex.com/).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[label](../schemas/label/label.md)

