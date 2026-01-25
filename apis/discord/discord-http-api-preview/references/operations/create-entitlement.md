# POST /applications/{application_id}/entitlements

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `create_entitlement`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateEntitlementRequestData](../schemas/Create/CreateEntitlementRequestData.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_entitlement |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[EntitlementResponse](../schemas/Entitlement/EntitlementResponse.md)

## Security

- **BotToken**
