# GET /accounts/{account_id}/botnet_feed/asn/{asn_id}/full_report

**Resource:** [Botnet Threat Feed](../resources/Botnet-Threat-Feed.md)
**Get full report**
**Operation ID:** `botnet-threat-feed-get-full-report`

Gets all the data the botnet threat feed tracking database has for a given ASN registered to user account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes |  |
| `asn_id` | path | dos_asn | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get full botnet feed report |
| 4XX | Get full botnet feed report response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
