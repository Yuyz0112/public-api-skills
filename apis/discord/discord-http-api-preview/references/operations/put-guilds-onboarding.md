# PUT /guilds/{guild_id}/onboarding

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `put_guilds_onboarding`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateGuildOnboardingRequest](../schemas/Update/UpdateGuildOnboardingRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for put_guilds_onboarding |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildOnboardingResponse](../schemas/Guild/GuildOnboardingResponse.md)

## Security

- **BotToken**
