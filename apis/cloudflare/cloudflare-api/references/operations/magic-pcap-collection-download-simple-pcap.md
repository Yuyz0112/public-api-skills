# GET /accounts/{account_id}/pcaps/{pcap_id}/download

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**Download Simple PCAP**
**Operation ID:** `magic-pcap-collection-download-simple-pcap`

Download PCAP information into a file. Response is a binary PCAP file.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pcap_id` | path | magic-visibility-pcaps_identifier | Yes |  |
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Download Simple PCAP response. |
| default | Download Simple PCAP response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
