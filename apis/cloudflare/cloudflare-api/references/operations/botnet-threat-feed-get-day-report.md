# GET /accounts/{account_id}/botnet_feed/asn/{asn_id}/day_report

**Resource:** [Botnet Threat Feed](../resources/Botnet-Threat-Feed.md)
**Get daily report**
**Operation ID:** `botnet-threat-feed-get-day-report`

Gets all the data the botnet tracking database has for a given ASN registered to user account for given date. If no date is given, it will return results for the previous day.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes |  |
| `asn_id` | path | dos_asn | Yes |  |
| `date` | query | dos_timestamp | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get botnet feed report for day |
| 4XX | Get botnet feed report for day response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
