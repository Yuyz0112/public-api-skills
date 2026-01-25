# POST /interactions/{interaction_id}/{interaction_token}/callback

**Resource:** [interactions](../resources/interactions.md)
**Operation ID:** `create_interaction_response`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_response` | query | boolean | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_interaction_response |
| 204 | 204 response for create_interaction_response |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[InteractionCallbackResponse](../schemas/Interaction/InteractionCallbackResponse.md)

## Security

- **BotToken**
