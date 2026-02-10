# PUT /api/v4/projects/{id}/mirror/pull

**Resource:** [Project mirrors](../resources/Project-mirrors.md)
**Update a pull mirror**
**Operation ID:** `putApiV4ProjectsIdMirrorPull`

This feature was introduced in GitLab 17.5. \
                    This feature is currently in an experimental state.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Url is blocked: Only allowed schemes are http, https, ssh, git |

**Success Response Schema:**

[APIEntitiesPullMirror](../schemas/APIEntitiesPullMirror/APIEntitiesPullMirror.md)

