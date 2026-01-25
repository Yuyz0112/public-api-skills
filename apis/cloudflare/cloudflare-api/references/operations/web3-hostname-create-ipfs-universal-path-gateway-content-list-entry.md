# POST /zones/{zone_id}/web3/hostnames/{identifier}/ipfs_universal_path/content_list/entries

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**Create IPFS Universal Path Gateway Content List Entry**
**Operation ID:** `web3-hostname-create-ipfs-universal-path-gateway-content-list-entry`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [web3_content_list_entry_create_request](../schemas/web3/web3-content-list-entry-create-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create IPFS Universal Path Gateway Content List Entry response. |
| 4XX | Create IPFS Universal Path Gateway Content List Entry error response (4XX). |
| 5XX | Create IPFS Universal Path Gateway Content List Entry response failure. |

**Success Response Schema:**

[web3_content_list_entry_single_response](../schemas/web3/web3-content-list-entry-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
