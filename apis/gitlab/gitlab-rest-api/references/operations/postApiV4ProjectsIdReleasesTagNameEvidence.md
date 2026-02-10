# POST /api/v4/projects/{id}/releases/{tag_name}/evidence

**Resource:** [Releases](../resources/Releases.md)
**Collect release evidence**
**Operation ID:** `postApiV4ProjectsIdReleasesTagNameEvidence`

Creates an evidence for an existing Release. This feature was introduced in GitLab 12.10.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tag_name` | path | string | Yes | The Git tag the release is associated with |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRelease](../schemas/APIEntitiesRelease/APIEntitiesRelease.md)

