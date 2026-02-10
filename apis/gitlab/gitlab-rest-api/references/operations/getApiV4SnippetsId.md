# GET /api/v4/snippets/{id}

**Resource:** [Snippets](../resources/Snippets.md)
**Get a single snippet**
**Operation ID:** `getApiV4SnippetsId`

This feature was introduced in GitLab 8.15.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a snippet |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesPersonalSnippet](../schemas/APIEntitiesPersonalSnippet/APIEntitiesPersonalSnippet.md)

