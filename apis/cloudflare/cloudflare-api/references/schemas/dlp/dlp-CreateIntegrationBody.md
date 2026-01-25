# dlp_CreateIntegrationBody

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `integration_type` | [dlp_RiskScoreIntegrationType](dlp-RiskScoreIntegrationType.md) | Yes |  |
| `reference_id` | string | No | A reference id that can be supplied by the client. Currently this should be set to the Access-Okta IDP ID (a UUIDv4).
https://developers.cloudflare.com/api/operations/access-identity-providers-get-an-access-identity-provider |
| `tenant_url` | string (uri) | Yes | The base url of the tenant, e.g. "https://tenant.okta.com". |

