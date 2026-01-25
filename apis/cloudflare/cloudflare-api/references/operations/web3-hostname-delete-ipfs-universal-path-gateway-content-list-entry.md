# DELETE /zones/{zone_id}/web3/hostnames/{identifier}/ipfs_universal_path/content_list/entries/{content_list_entry_identifier}

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**Delete IPFS Universal Path Gateway Content List Entry**
**Operation ID:** `web3-hostname-delete-ipfs-universal-path-gateway-content-list-entry`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `content_list_entry_identifier` | path | web3_identifier | Yes |  |
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete IPFS Universal Path Gateway Content List Entry response. |
| 4XX | Delete IPFS Universal Path Gateway Content List Entry error response (4XX). |
| 5XX | Delete IPFS Universal Path Gateway Content List Entry response failure. |

**Success Response Schema:**

[web3_api-response-single-id](../schemas/web3/web3-api-response-single-id.md)

## Security

- **api_email**
- **api_key**
- **api_token**
