# POST /accounts/{account_id}/pay-per-crawl/zones_can_be_enabled/query

**Resource:** [ppc_config](../resources/ppc-config.md)
**Gets the can_be_enabled zone setting**
**Operation ID:** `pay-per-crawl.queryZonesCanBeEnabled`

Provided a list of pay-per-crawl configured zones this method will return whether they can enable PPC or not.

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

[pay-per-crawl_queryZonesCanBeEnabledResponse](../schemas/pay-per-crawl/pay-per-crawl-queryZonesCanBeEnabledResponse.md)

## Security

- **api_email**
- **api_key**
