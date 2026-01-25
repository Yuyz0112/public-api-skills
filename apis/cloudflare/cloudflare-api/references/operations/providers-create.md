# POST /accounts/{account_id}/magic/cloud/providers

**Resource:** [Cloud Integrations](../resources/Cloud-Integrations.md)
**Create Cloud Integration**
**Operation ID:** `providers-create`

Create a new Cloud Integration (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `forwarded` | header | string | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mcn_create_provider_request](../schemas/mcn/mcn-create-provider-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 409 | Conflict. |
| 422 | Unprocessable Entity. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_create_provider_response](../schemas/mcn/mcn-create-provider-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
