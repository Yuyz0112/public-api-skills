# GET /accounts/{account_id}/pcaps

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**List packet capture requests**
**Operation ID:** `magic-pcap-collection-list-packet-capture-requests`

Lists all packet capture requests for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List packet capture requests response. |
| default | List packet capture requests response failure. |

**Success Response Schema:**

[magic-visibility-pcaps_pcaps_collection_response](../schemas/magic-visibility-pcaps/magic-visibility-pcaps-pcaps-collection-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
