# GET /zones/{zone_id}/web3/hostnames/{identifier}

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**Web3 Hostname Details**
**Operation ID:** `web3-hostname-web3-hostname-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Web3 Hostname Details response. |
| 4XX | Web3 Hostname Details error response (4XX). |
| 5XX | Web3 Hostname Details response failure. |

**Success Response Schema:**

[web3_single_response](../schemas/web3/web3-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
