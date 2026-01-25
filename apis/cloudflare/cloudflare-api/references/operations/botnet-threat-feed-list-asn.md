# GET /accounts/{account_id}/botnet_feed/configs/asn

**Resource:** [Botnet Threat Feed](../resources/Botnet-Threat-Feed.md)
**Get list of ASNs**
**Operation ID:** `botnet-threat-feed-list-asn`

Gets a list of all ASNs registered for a user for the DDoS Botnet Feed API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get list of ASNs response |
| 4XX | Get list of ASNs response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
