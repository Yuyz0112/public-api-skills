# POST /accounts/{account_id}/cni/cnis

**Resource:** [CNIs](../resources/CNIs.md)
**Create a new CNI object**
**Operation ID:** `create_cni`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | nsc_AccountTag | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [nsc_CniCreate](../schemas/nsc/nsc-CniCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | CNI was successfully created |
| 400 | Bad request |
| 409 | Name Conflict |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_Cni](../schemas/nsc/nsc-Cni.md)

## Security

- **api_email**
- **api_key**
- **api_token**
