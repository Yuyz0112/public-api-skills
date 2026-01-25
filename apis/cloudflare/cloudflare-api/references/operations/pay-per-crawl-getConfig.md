# GET /zones/{zone_id}/pay-per-crawl/configuration

**Resource:** [ppc_config](../resources/ppc-config.md)
**Get the pay-per-crawl config**
**Operation ID:** `pay-per-crawl.getConfig`

Gets the pay-per-crawl config for a zone including the bot configuration.

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
