# GET /accounts/{account_id}/pcaps/{pcap_id}

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**Get PCAP request**
**Operation ID:** `magic-pcap-collection-get-pcap-request`

Get information for a PCAP request by id.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pcap_id` | path | magic-visibility-pcaps_identifier | Yes |  |
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get PCAP request response. |
| default | Get PCAP request response failure. |

**Success Response Schema:**

[magic-visibility-pcaps_pcaps_single_response](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
