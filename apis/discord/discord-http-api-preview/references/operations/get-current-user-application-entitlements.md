# GET /users/@me/applications/{application_id}/entitlements

**Resource:** [users](../resources/users.md)
**Operation ID:** `get_current_user_application_entitlements`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sku_ids` | query | any | No |  |
| `exclude_consumed` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_current_user_application_entitlements |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **OAuth2**: activities.invites.write, activities.read, activities.write, applications.builds.read, applications.builds.upload, applications.commands, applications.commands.permissions.update, applications.commands.update, applications.entitlements, applications.store.update, bot, connections, dm_channels.read, email, gdm.join, guilds, guilds.join, guilds.members.read, identify, messages.read, openid, relationships.read, role_connections.write, rpc, rpc.activities.write, rpc.notifications.read, rpc.screenshare.read, rpc.screenshare.write, rpc.video.read, rpc.video.write, rpc.voice.read, rpc.voice.write, voice, webhook.incoming
