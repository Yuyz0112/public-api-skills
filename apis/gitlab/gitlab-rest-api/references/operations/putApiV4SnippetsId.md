# PUT /api/v4/snippets/{id}

**Resource:** [Snippets](../resources/Snippets.md)
**Update an existing snippet**
**Operation ID:** `putApiV4SnippetsId`

This feature was introduced in GitLab 8.15.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a snippet |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesPersonalSnippet](../schemas/APIEntitiesPersonalSnippet/APIEntitiesPersonalSnippet.md)

