# PATCH /applications/{application_id}

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `update_application`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ApplicationFormPartial](../schemas/Application/ApplicationFormPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_application |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[PrivateApplicationResponse](../schemas/Private/PrivateApplicationResponse.md)

## Security

- **BotToken**
