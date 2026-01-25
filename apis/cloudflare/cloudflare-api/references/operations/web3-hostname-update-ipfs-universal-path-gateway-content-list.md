# PUT /zones/{zone_id}/web3/hostnames/{identifier}/ipfs_universal_path/content_list

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**Update IPFS Universal Path Gateway Content List**
**Operation ID:** `web3-hostname-update-ipfs-universal-path-gateway-content-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [web3_content_list_update_request](../schemas/web3/web3-content-list-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update IPFS Universal Path Gateway Content List response. |
| 4XX | Update IPFS Universal Path Gateway Content List error response (4XX). |
| 5XX | Update IPFS Universal Path Gateway Content List response failure. |

**Success Response Schema:**

[web3_content_list_details_response](../schemas/web3/web3-content-list-details-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
