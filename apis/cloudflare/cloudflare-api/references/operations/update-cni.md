# PUT /accounts/{account_id}/cni/cnis/{cni}

**Resource:** [CNIs](../resources/CNIs.md)
**Modify stored information about a CNI object**
**Operation ID:** `update_cni`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cni` | path | string (uuid) | Yes | CNI ID to retrieve information about |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [nsc_Cni](../schemas/nsc/nsc-Cni.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | CNI has been successfully modified |
| 400 | Bad request |
| 404 | CNI not found |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_Cni](../schemas/nsc/nsc-Cni.md)

## Security

- **api_email**
- **api_key**
- **api_token**
