# GET /v1/teams/{team_id}/projects

**Resource:** [Projects](../resources/Projects.md)
**Get projects in a team**
**Operation ID:** `getTeamProjects`

You can use this endpoint to get a list of all the Projects within the specified team. This will only return projects visible to the authenticated user or owner of the developer token. Note: it is not currently possible to programmatically obtain the team id of a user just from a token. To obtain a team id, navigate to a team page of a team you are a part of. The team id will be present in the URL after the word team and before your team name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `team_id` | path | string | Yes | ID of the team to list projects from |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: projects:read, files:read
