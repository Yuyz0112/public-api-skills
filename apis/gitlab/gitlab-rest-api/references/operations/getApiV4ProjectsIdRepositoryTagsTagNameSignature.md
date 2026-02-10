# GET /api/v4/projects/{id}/repository/tags/{tag_name}/signature

**Resource:** [Tags](../resources/Tags.md)
**Get a tag's signature**
**Operation ID:** `getApiV4ProjectsIdRepositoryTagsTagNameSignature`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The name of the tag |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesTagSignature](../schemas/APIEntitiesTagSignature/APIEntitiesTagSignature.md)

