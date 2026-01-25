# GET /migration.exchange

**Resource:** [migration](../resources/migration.md)
**Operation ID:** `migration_exchange`

For Enterprise Grid workspaces, map local user IDs to global user IDs

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `tokens.basic` |
| `users` | query | string | Yes | A comma-separated list of user ids, up to 400 per request |
| `team_id` | query | string | No | Specify team_id starts with `T` in case of Org Token |
| `to_old` | query | boolean | No | Specify `true` to convert `W` global user IDs to workspace-specific `U` IDs. Defaults to `false`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response when mappings exist for the specified user IDs |
| default | Typical error response when there are no mappings to provide |

## Security

- **slackAuth**: tokens.basic
