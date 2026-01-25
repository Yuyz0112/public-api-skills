# DELETE /zones/{zone_id}/web3/hostnames/{identifier}

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**Delete Web3 Hostname**
**Operation ID:** `web3-hostname-delete-web3-hostname`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Web3 Hostname response. |
| 4XX | Delete Web3 Hostname error response (4XX). |
| 5XX | Delete Web3 Hostname response failure. |

**Success Response Schema:**

[web3_api-response-single-id](../schemas/web3/web3-api-response-single-id.md)

## Security

- **api_email**
- **api_key**
- **api_token**
