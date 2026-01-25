# GET /v2/teams/{team_id}/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**[Deprecated] Get team webhooks**
**Operation ID:** `getTeamWebhooks`
⚠️ **Deprecated**

Returns all webhooks registered under the specified team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `team_id` | path | string | Yes | ID of team to get webhooks for |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: webhooks:read, files:read
