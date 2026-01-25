# PATCH /accounts/{account_id}/magic/cloud/providers/{provider_id}

**Resource:** [Cloud Integrations](../resources/Cloud-Integrations.md)
**Patch Cloud Integration**
**Operation ID:** `providers-patch`

Update a Cloud Integration (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `provider_id` | path | mcn_provider_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mcn_update_provider_request](../schemas/mcn/mcn-update-provider-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 409 | Conflict. |
| 422 | Unprocessable Entity. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_update_provider_response](../schemas/mcn/mcn-update-provider-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
