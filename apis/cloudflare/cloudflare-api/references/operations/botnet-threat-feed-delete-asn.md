# DELETE /accounts/{account_id}/botnet_feed/configs/asn/{asn_id}

**Resource:** [Botnet Threat Feed](../resources/Botnet-Threat-Feed.md)
**Delete an ASN**
**Operation ID:** `botnet-threat-feed-delete-asn`

Delete an ASN from botnet threat feed for a given user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes |  |
| `asn_id` | path | dos_asn | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete ASN response |
| 4XX | Delete ASN response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
