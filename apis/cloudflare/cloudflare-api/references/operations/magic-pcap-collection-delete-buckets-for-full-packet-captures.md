# DELETE /accounts/{account_id}/pcaps/ownership/{ownership_id}

**Resource:** [Magic PCAP collection](../resources/Magic-PCAP-collection.md)
**Delete buckets for full packet captures**
**Operation ID:** `magic-pcap-collection-delete-buckets-for-full-packet-captures`

Deletes buckets added to the packet captures API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ownership_id` | path | magic-visibility-pcaps_identifier | Yes |  |
| `account_id` | path | magic-visibility-pcaps_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Delete buckets for full packet captures response. |
| default | Delete buckets for full packet captures response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
