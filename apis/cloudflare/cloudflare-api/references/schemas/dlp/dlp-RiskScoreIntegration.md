# dlp_RiskScoreIntegration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_tag` | string | Yes | The Cloudflare account tag. |
| `active` | boolean | Yes | Whether this integration is enabled and should export changes in risk score. |
| `created_at` | string (date-time) | Yes | When the integration was created in RFC3339 format. |
| `id` | string (uuid) | Yes | The id of the integration, a UUIDv4. |
| `integration_type` | [dlp_RiskScoreIntegrationType](dlp-RiskScoreIntegrationType.md) | Yes |  |
| `reference_id` | string | Yes | A reference ID defined by the client.
Should be set to the Access-Okta IDP integration ID.
Useful when the risk-score integration needs to be associated with a secondary asset and recalled using that ID. |
| `tenant_url` | string | Yes | The base URL for the tenant. E.g. "https://tenant.okta.com". |
| `well_known_url` | string | Yes | The URL for the Shared Signals Framework configuration, e.g. "/.well-known/sse-configuration/{integration_uuid}/". https://openid.net/specs/openid-sse-framework-1_0.html#rfc.section.6.2.1. |

