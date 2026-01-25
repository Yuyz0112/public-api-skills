# GET /accounts/{account_id}/intel/dns

**Resource:** [Passive DNS by IP](../resources/Passive-DNS-by-IP.md)
**Get Passive DNS by IP**
**Operation ID:** `passive-dns-by-ip-get-passive-dns-by-ip`

Gets a list of all the domains that have resolved to a specific IP address.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel_identifier | Yes |  |
| `start_end_params` | query | intel_start_end_params | No |  |
| `ipv4` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Passive DNS by IP response. |
| 4XX | Get Passive DNS by IP response failure. |

**Success Response Schema:**

[intel_components-schemas-single_response](../schemas/intel/intel-components-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
