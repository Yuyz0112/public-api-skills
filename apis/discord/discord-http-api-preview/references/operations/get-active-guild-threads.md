# GET /guilds/{guild_id}/threads/active

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `get_active_guild_threads`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_active_guild_threads |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ThreadsResponse](../schemas/Threads/ThreadsResponse.md)

## Security

- **BotToken**
