# GET /oauth2/@me

**Resource:** [oauth2](../resources/oauth2.md)
**Operation ID:** `get_my_oauth2_authorization`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_my_oauth2_authorization |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[OAuth2GetAuthorizationResponse](../schemas/OAuth2GetAuthorizationResponse/OAuth2GetAuthorizationResponse.md)

## Security

- **BotToken**
- **OAuth2**: activities.invites.write, activities.read, activities.write, applications.builds.read, applications.builds.upload, applications.commands, applications.commands.permissions.update, applications.commands.update, applications.entitlements, applications.store.update, bot, connections, dm_channels.read, email, gdm.join, guilds, guilds.join, guilds.members.read, identify, messages.read, openid, relationships.read, role_connections.write, rpc, rpc.activities.write, rpc.notifications.read, rpc.screenshare.read, rpc.screenshare.write, rpc.video.read, rpc.video.write, rpc.voice.read, rpc.voice.write, voice, webhook.incoming
