# POST /accounts/{account_id}/cni/interconnects

**Resource:** [Interconnects](../resources/Interconnects.md)
**Create a new interconnect**
**Operation ID:** `create_interconnect`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | nsc_AccountTag | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [nsc_InterconnectCreate](../schemas/nsc/nsc-InterconnectCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Information about the new interconnect |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_Interconnect](../schemas/nsc/nsc-Interconnect.md)

## Security

- **api_email**
- **api_key**
- **api_token**
