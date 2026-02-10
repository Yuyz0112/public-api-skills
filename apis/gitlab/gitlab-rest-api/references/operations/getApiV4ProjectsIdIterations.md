# GET /api/v4/projects/{id}/iterations

**Resource:** [Iterations](../resources/Iterations.md)
**Get a list of project iterations**
**Operation ID:** `getApiV4ProjectsIdIterations`

This feature was introduced in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `state` | query | enum: opened, upcoming, started... | No | Return "opened", "upcoming", "current (previously started)", "closed", or "all" iterations. Filtering by `started` state is deprecated starting with 14.1, please use `current` instead. |
| `search` | query | string | No | The search criteria for the title of the iteration |
| `in` | query | any | No | Fields in which fuzzy search should be performed with the query given in the argument `search`. The available options are `title` and `cadence_title`. Defaults to `[title]` |
| `include_ancestors` | query | boolean | No | Include iterations from parent and its ancestors |
| `include_descendants` | query | boolean | No | Include iterations from parent and its descendants |
| `updated_before` | query | string (date-time) | No | Return milestones updated before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `updated_after` | query | string (date-time) | No | Return milestones updated after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIteration](../schemas/APIEntitiesIteration/APIEntitiesIteration.md)

