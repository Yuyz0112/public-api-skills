# GET /v1/teams/{team_id}/component_sets

**Resource:** [Component Sets](../resources/Component-Sets.md)
**Get team component sets**
**Operation ID:** `getTeamComponentSets`

Get a paginated list of published component sets within a team library.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `team_id` | path | string | Yes | Id of the team to list component sets from. |
| `page_size` | query | number | No | Number of items to return in a paged list of results. Defaults to 30. |
| `after` | query | number | No | Cursor indicating which id after which to start retrieving component sets for. Exclusive with before. The cursor value is an internally tracked integer that doesn't correspond to any Ids. |
| `before` | query | number | No | Cursor indicating which id before which to start retrieving component sets for. Exclusive with after. The cursor value is an internally tracked integer that doesn't correspond to any Ids. |

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
