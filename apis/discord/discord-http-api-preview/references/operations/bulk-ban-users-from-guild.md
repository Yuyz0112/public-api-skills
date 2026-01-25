# POST /guilds/{guild_id}/bulk-ban

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `bulk_ban_users_from_guild`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkBanUsersRequest](../schemas/Bulk/BulkBanUsersRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for bulk_ban_users_from_guild |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[BulkBanUsersResponse](../schemas/Bulk/BulkBanUsersResponse.md)

## Security

- **BotToken**
