# GET /v1/teams/{team_id}/components

**Resource:** [Components](../resources/Components.md)
**Get team components**
**Operation ID:** `getTeamComponents`

Get a paginated list of published components within a team library.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `team_id` | path | string | Yes | Id of the team to list components from. |
| `page_size` | query | number | No | Number of items to return in a paged list of results. Defaults to 30. Maximum of 1000. |
| `after` | query | number | No | Cursor indicating which id after which to start retrieving components for. Exclusive with before. The cursor value is an internally tracked integer that doesn't correspond to any Ids. |
| `before` | query | number | No | Cursor indicating which id before which to start retrieving components for. Exclusive with after. The cursor value is an internally tracked integer that doesn't correspond to any Ids. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: team_library_content:read, files:read
