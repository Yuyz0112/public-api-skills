# GET /applications/{application_id}/entitlements/{entitlement_id}

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `get_entitlement`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_entitlement |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[EntitlementResponse](../schemas/Entitlement/EntitlementResponse.md)

## Security

- **BotToken**
- **OAuth2**: applications.entitlements
