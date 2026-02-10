# POST /api/v4/projects/{id}/mirror/pull

**Resource:** [Project mirrors](../resources/Project-mirrors.md)
**Triggers a pull mirror operation**
**Operation ID:** `postApiV4ProjectsIdMirrorPull`

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
| 400 | The project is not mirrored |
| 403 | Mirroring for the project is on pause |
| 422 | The pull request event is not processable |

