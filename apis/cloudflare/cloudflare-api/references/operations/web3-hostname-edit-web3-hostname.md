# PATCH /zones/{zone_id}/web3/hostnames/{identifier}

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**Edit Web3 Hostname**
**Operation ID:** `web3-hostname-edit-web3-hostname`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | web3_identifier | Yes |  |
| `zone_id` | path | web3_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [web3_modify_request](../schemas/web3/web3-modify-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit Web3 Hostname response. |
| 4XX | Edit Web3 Hostname error response (4XX). |
| 5XX | Edit Web3 Hostname response failure. |

**Success Response Schema:**

[web3_single_response](../schemas/web3/web3-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
