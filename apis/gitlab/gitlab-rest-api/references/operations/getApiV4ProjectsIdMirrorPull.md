# GET /api/v4/projects/{id}/mirror/pull

**Resource:** [Project mirrors](../resources/Project-mirrors.md)
**Get a pull mirror**
**Operation ID:** `getApiV4ProjectsIdMirrorPull`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | The project is not mirrored |

**Success Response Schema:**

[APIEntitiesPullMirror](../schemas/APIEntitiesPullMirror/APIEntitiesPullMirror.md)

