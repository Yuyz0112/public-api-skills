# GET /zones/{zone_id}/web3/hostnames

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**List Web3 Hostnames**
**Operation ID:** `web3-hostname-list-web3-hostnames`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | web3_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Web3 Hostnames response. |
| 4XX | List Web3 Hostnames error response (4XX). |
| 5XX | List Web3 Hostnames response failure. |

**Success Response Schema:**

[web3_collection_response](../schemas/web3/web3-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
