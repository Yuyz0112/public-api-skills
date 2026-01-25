# GET /zones/{zone_id}/web3/hostnames/{identifier}/ipfs_universal_path/content_list/entries/{content_list_entry_identifier}

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**IPFS Universal Path Gateway Content List Entry Details**
**Operation ID:** `web3-hostname-ipfs-universal-path-gateway-content-list-entry-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `content_list_entry_identifier` | path | web3_identifier | Yes |  |
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | IPFS Universal Path Gateway Content List Entry Details response. |
| 4XX | IPFS Universal Path Gateway Content List Entry Details error response (4XX). |
| 5XX | IPFS Universal Path Gateway Content List Entry Details response failure. |

**Success Response Schema:**

[web3_content_list_entry_single_response](../schemas/web3/web3-content-list-entry-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
