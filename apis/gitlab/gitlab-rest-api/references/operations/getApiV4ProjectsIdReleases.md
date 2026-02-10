# GET /api/v4/projects/{id}/releases

**Resource:** [Releases](../resources/Releases.md)
**List Releases**
**Operation ID:** `getApiV4ProjectsIdReleases`

Returns a paginated list of releases. This feature was introduced in GitLab 11.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `order_by` | query | enum: released_at, created_at | No | The field to use as order. Either `released_at` (default) or `created_at` |
| `sort` | query | enum: asc, desc | No | The direction of the order. Either `desc` (default) for descending order or `asc` for ascending order |
| `include_html_description` | query | boolean | No | If `true`, a response includes HTML rendered markdown of the release description |
| `updated_before` | query | string (date-time) | No | Return releases updated before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `updated_after` | query | string (date-time) | No | Return releases updated after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesRelease](../schemas/APIEntitiesRelease/APIEntitiesRelease.md)

