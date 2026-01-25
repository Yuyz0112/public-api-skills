# POST /zones/{zone_id}/web3/hostnames

**Resource:** [Web3 Hostname](../resources/Web3-Hostname.md)
**Create Web3 Hostname**
**Operation ID:** `web3-hostname-create-web3-hostname`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | web3_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [web3_create_request](../schemas/web3/web3-create-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Web3 Hostname response. |
| 4XX | Create Web3 Hostname error response (4XX). |
| 5XX | Create Web3 Hostname response failure. |

**Success Response Schema:**

[web3_single_response](../schemas/web3/web3-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
