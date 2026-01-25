# POST /channels/{channel_id}/threads

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `create_thread`

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_thread |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[CreatedThreadResponse](../schemas/Created/CreatedThreadResponse.md)

## Security

- **BotToken**
