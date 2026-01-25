# POST /applications/{application_id}/attachment

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `upload_application_attachment`

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for upload_application_attachment |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ActivitiesAttachmentResponse](../schemas/Activities/ActivitiesAttachmentResponse.md)

## Security

- **BotToken**
- **OAuth2**: activities.invites.write, activities.read, activities.write, applications.builds.read, applications.builds.upload, applications.commands, applications.commands.permissions.update, applications.commands.update, applications.entitlements, applications.store.update, bot, connections, dm_channels.read, email, gdm.join, guilds, guilds.join, guilds.members.read, identify, messages.read, openid, relationships.read, role_connections.write, rpc, rpc.activities.write, rpc.notifications.read, rpc.screenshare.read, rpc.screenshare.write, rpc.video.read, rpc.video.write, rpc.voice.read, rpc.voice.write, voice, webhook.incoming
