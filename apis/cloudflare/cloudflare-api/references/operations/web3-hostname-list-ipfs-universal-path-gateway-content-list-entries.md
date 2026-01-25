# GET /zones/{zone_id}/web3/hostnames/{identifier}/ipfs_universal_path/content_list/entries

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**List IPFS Universal Path Gateway Content List Entries**
**Operation ID:** `web3-hostname-list-ipfs-universal-path-gateway-content-list-entries`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List IPFS Universal Path Gateway Content List Entries response. |
| 4XX | List IPFS Universal Path Gateway Content List Entries error response (4XX). |
| 5XX | List IPFS Universal Path Gateway Content List Entries response failure. |

**Success Response Schema:**

[web3_content_list_entry_collection_response](../schemas/web3/web3-content-list-entry-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
