# GET /zones/{zone_id}/ssl/recommendation

**Resource:** [SSL/TLS Mode Recommendation](../resources/SSL-TLS-Mode-Recommendation.md)
**SSL/TLS Recommendation**
**Operation ID:** `ssl/-tls-mode-recommendation-ssl/-tls-recommendation`
⚠️ **Deprecated**

Retrieve the SSL/TLS Recommender's recommendation for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | SSL/TLS Recommendation response. |
| 4XX | SSL/TLS Recommendation response failure. |

**Success Response Schema:**

[cache_api-response-single-id](../schemas/cache/cache-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
