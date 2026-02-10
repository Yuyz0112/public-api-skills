# GET /api/v4/groups/{id}/releases

**Resource:** [Releases](../resources/Releases.md)
**List group releases**
**Operation ID:** `getApiV4GroupsIdReleases`

Returns a list of group releases.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `sort` | query | enum: asc, desc | No | The direction of the order. Either `desc` (default) for descending order or `asc` for ascending order |
| `simple` | query | boolean | No | Return only limited fields for each release |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRelease](../schemas/APIEntitiesRelease/APIEntitiesRelease.md)

