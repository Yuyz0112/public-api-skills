# PATCH /accounts/{account_id}/pay-per-crawl/zones_can_be_enabled

**Resource:** [ppc_config](../resources/ppc-config.md)
**Set can_be_enabled setting on zones**
**Operation ID:** `pay-per-crawl.setZonesCanBeEnabled`

Allows an account admin to set the can_be_enabled setting on a list of zones.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | account id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

**Success Response Schema:**

[pay-per-crawl_apiNoResultResponse](../schemas/pay-per-crawl/pay-per-crawl-apiNoResultResponse.md)

## Security

- **api_email**
- **api_key**
