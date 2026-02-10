# PUT /api/v4/projects/{id}/releases/{tag_name}

**Resource:** [Releases](../resources/Releases.md)
**Update a release**
**Operation ID:** `putApiV4ProjectsIdReleasesTagName`

Updates a release. Developer level access to the project is required to update a release. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The Git tag the release is associated with |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRelease](../schemas/APIEntitiesRelease/APIEntitiesRelease.md)

