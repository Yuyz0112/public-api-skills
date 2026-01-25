# Authentication

This document describes the authentication methods supported by this API.

## BotToken

**Type:** apiKey

Discord bot token

- **In:** header

## OAuth2

**Type:** oauth2

**implicit flow:**
- Authorization URL: https://discord.com/api/oauth2/authorize
- Scopes:
  - `activities.invites.write`: allows your app to send activity invites - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
  - `activities.read`: allows your app to fetch data from a user's "Now Playing/Recently Played" list - requires Discord approval
  - `activities.write`: allows your app to update a user's activity - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
  - `applications.builds.read`: allows your app to read build data for a user's applications
  - `applications.builds.upload`: allows your app to upload/update builds for a user's applications - requires Discord approval
  - `applications.commands`: allows your app to use commands in a guild
  - `applications.commands.permissions.update`: allows your app to update permissions for its commands in a guild a user has permissions to
  - `applications.entitlements`: allows your app to read entitlements for a user's applications
  - `applications.store.update`: allows your app to read and update store data (SKUs, store listings, achievements, etc.) for a user's applications
  - `bot`: for oauth2 bots, this puts the bot in the user's selected guild by default
  - `connections`: allows /users/@me/connections to return linked third-party accounts
  - `dm_channels.read`: allows your app to see information about the user's DMs and group DMs - requires Discord approval
  - `email`: enables /users/@me to return an email
  - `gdm.join`: allows your app to join users to a group dm
  - `guilds`: allows /users/@me/guilds to return basic information about all of a user's guilds
  - `guilds.join`: allows /guilds/{guild.id}/members/{user.id} to be used for joining users to a guild
  - `guilds.members.read`: allows /users/@me/guilds/{guild.id}/member to return a user's member information in a guild
  - `identify`: allows /users/@me without email
  - `messages.read`: for local rpc server api access, this allows you to read messages from all client channels (otherwise restricted to channels/guilds your app creates)
  - `openid`: for OpenID Connect, this allows your app to receive user id and basic profile information
  - `relationships.read`: allows your app to know a user's friends and implicit relationships - requires Discord approval
  - `rpc`: for local rpc server access, this allows you to control a user's local Discord client - requires Discord approval
  - `rpc.activities.write`: for local rpc server access, this allows you to update a user's activity - requires Discord approval
  - `rpc.notifications.read`: for local rpc server access, this allows you to receive notifications pushed out to the user - requires Discord approval
  - `rpc.screenshare.read`: for local rpc server access, this allows you to read a user's screenshare status- requires Discord approval
  - `rpc.screenshare.write`: for local rpc server access, this allows you to update a user's screenshare settings- requires Discord approval
  - `rpc.video.read`: for local rpc server access, this allows you to read a user's video status - requires Discord approval
  - `rpc.video.write`: for local rpc server access, this allows you to update a user's video settings - requires Discord approval
  - `rpc.voice.read`: for local rpc server access, this allows you to read a user's voice settings and listen for voice events - requires Discord approval
  - `rpc.voice.write`: for local rpc server access, this allows you to update a user's voice settings - requires Discord approval
  - `voice`: allows your app to connect to voice on user's behalf and see all the voice members - requires Discord approval
  - `webhook.incoming`: this generates a webhook that is returned in the oauth token response for authorization code grants

**clientCredentials flow:**
- Token URL: https://discord.com/api/oauth2/token
- Scopes:
  - `activities.invites.write`: allows your app to send activity invites - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
  - `activities.read`: allows your app to fetch data from a user's "Now Playing/Recently Played" list - requires Discord approval
  - `activities.write`: allows your app to update a user's activity - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
  - `applications.builds.read`: allows your app to read build data for a user's applications
  - `applications.builds.upload`: allows your app to upload/update builds for a user's applications - requires Discord approval
  - `applications.commands`: allows your app to use commands in a guild
  - `applications.commands.permissions.update`: allows your app to update permissions for its commands in a guild a user has permissions to
  - `applications.commands.update`: allows your app to update its commands using a Bearer token - client credentials grant only
  - `applications.entitlements`: allows your app to read entitlements for a user's applications
  - `applications.store.update`: allows your app to read and update store data (SKUs, store listings, achievements, etc.) for a user's applications
  - `bot`: for oauth2 bots, this puts the bot in the user's selected guild by default
  - `connections`: allows /users/@me/connections to return linked third-party accounts
  - `dm_channels.read`: allows your app to see information about the user's DMs and group DMs - requires Discord approval
  - `email`: enables /users/@me to return an email
  - `gdm.join`: allows your app to join users to a group dm
  - `guilds`: allows /users/@me/guilds to return basic information about all of a user's guilds
  - `guilds.join`: allows /guilds/{guild.id}/members/{user.id} to be used for joining users to a guild
  - `guilds.members.read`: allows /users/@me/guilds/{guild.id}/member to return a user's member information in a guild
  - `identify`: allows /users/@me without email
  - `messages.read`: for local rpc server api access, this allows you to read messages from all client channels (otherwise restricted to channels/guilds your app creates)
  - `openid`: for OpenID Connect, this allows your app to receive user id and basic profile information
  - `relationships.read`: allows your app to know a user's friends and implicit relationships - requires Discord approval
  - `rpc`: for local rpc server access, this allows you to control a user's local Discord client - requires Discord approval
  - `rpc.activities.write`: for local rpc server access, this allows you to update a user's activity - requires Discord approval
  - `rpc.notifications.read`: for local rpc server access, this allows you to receive notifications pushed out to the user - requires Discord approval
  - `rpc.screenshare.read`: for local rpc server access, this allows you to read a user's screenshare status- requires Discord approval
  - `rpc.screenshare.write`: for local rpc server access, this allows you to update a user's screenshare settings- requires Discord approval
  - `rpc.video.read`: for local rpc server access, this allows you to read a user's video status - requires Discord approval
  - `rpc.video.write`: for local rpc server access, this allows you to update a user's video settings - requires Discord approval
  - `rpc.voice.read`: for local rpc server access, this allows you to read a user's voice settings and listen for voice events - requires Discord approval
  - `rpc.voice.write`: for local rpc server access, this allows you to update a user's voice settings - requires Discord approval
  - `voice`: allows your app to connect to voice on user's behalf and see all the voice members - requires Discord approval
  - `webhook.incoming`: this generates a webhook that is returned in the oauth token response for authorization code grants

**authorizationCode flow:**
- Authorization URL: https://discord.com/api/oauth2/authorize
- Token URL: https://discord.com/api/oauth2/token
- Scopes:
  - `activities.invites.write`: allows your app to send activity invites - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
  - `activities.read`: allows your app to fetch data from a user's "Now Playing/Recently Played" list - requires Discord approval
  - `activities.write`: allows your app to update a user's activity - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
  - `applications.builds.read`: allows your app to read build data for a user's applications
  - `applications.builds.upload`: allows your app to upload/update builds for a user's applications - requires Discord approval
  - `applications.commands`: allows your app to use commands in a guild
  - `applications.commands.permissions.update`: allows your app to update permissions for its commands in a guild a user has permissions to
  - `applications.entitlements`: allows your app to read entitlements for a user's applications
  - `applications.store.update`: allows your app to read and update store data (SKUs, store listings, achievements, etc.) for a user's applications
  - `bot`: for oauth2 bots, this puts the bot in the user's selected guild by default
  - `connections`: allows /users/@me/connections to return linked third-party accounts
  - `dm_channels.read`: allows your app to see information about the user's DMs and group DMs - requires Discord approval
  - `email`: enables /users/@me to return an email
  - `gdm.join`: allows your app to join users to a group dm
  - `guilds`: allows /users/@me/guilds to return basic information about all of a user's guilds
  - `guilds.join`: allows /guilds/{guild.id}/members/{user.id} to be used for joining users to a guild
  - `guilds.members.read`: allows /users/@me/guilds/{guild.id}/member to return a user's member information in a guild
  - `identify`: allows /users/@me without email
  - `messages.read`: for local rpc server api access, this allows you to read messages from all client channels (otherwise restricted to channels/guilds your app creates)
  - `openid`: for OpenID Connect, this allows your app to receive user id and basic profile information
  - `relationships.read`: allows your app to know a user's friends and implicit relationships - requires Discord approval
  - `role_connections.write`: allows your app to update a user's connection and metadata for the app
  - `rpc`: for local rpc server access, this allows you to control a user's local Discord client - requires Discord approval
  - `rpc.activities.write`: for local rpc server access, this allows you to update a user's activity - requires Discord approval
  - `rpc.notifications.read`: for local rpc server access, this allows you to receive notifications pushed out to the user - requires Discord approval
  - `rpc.screenshare.read`: for local rpc server access, this allows you to read a user's screenshare status- requires Discord approval
  - `rpc.screenshare.write`: for local rpc server access, this allows you to update a user's screenshare settings- requires Discord approval
  - `rpc.video.read`: for local rpc server access, this allows you to read a user's video status - requires Discord approval
  - `rpc.video.write`: for local rpc server access, this allows you to update a user's video settings - requires Discord approval
  - `rpc.voice.read`: for local rpc server access, this allows you to read a user's voice settings and listen for voice events - requires Discord approval
  - `rpc.voice.write`: for local rpc server access, this allows you to update a user's voice settings - requires Discord approval
  - `voice`: allows your app to connect to voice on user's behalf and see all the voice members - requires Discord approval
  - `webhook.incoming`: this generates a webhook that is returned in the oauth token response for authorization code grants

