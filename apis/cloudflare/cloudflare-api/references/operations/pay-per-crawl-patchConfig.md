# PATCH /zones/{zone_id}/pay-per-crawl/configuration

**Resource:** [ppc_config](../resources/ppc-config.md)
**Changes pay-per-crawl config for a zone**
**Operation ID:** `pay-per-crawl.patchConfig`

Changes the pay-per-crawl config for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | string | Yes | zone id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

**Success Response Schema:**

[pay-per-crawl_getConfigResponse](../schemas/pay-per-crawl/pay-per-crawl-getConfigResponse.md)

## Security

- **api_email**
- **api_key**
