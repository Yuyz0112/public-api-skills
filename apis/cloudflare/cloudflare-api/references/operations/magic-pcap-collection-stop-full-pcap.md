# PUT /accounts/{account_id}/pcaps/{pcap_id}/stop

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**Stop full PCAP**
**Operation ID:** `magic-pcap-collection-stop-full-pcap`

Stop full PCAP.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pcap_id` | path | magic-visibility-pcaps_identifier | Yes |  |
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Stop full PCAP response. |
| default | Stop full PCAP response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
