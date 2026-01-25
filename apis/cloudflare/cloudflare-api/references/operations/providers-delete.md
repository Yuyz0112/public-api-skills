# DELETE /accounts/{account_id}/magic/cloud/providers/{provider_id}

**Resource:** [Cloud Integrations](../resources/Cloud-Integrations.md)
**Delete Cloud Integration**
**Operation ID:** `providers-delete`

Delete a Cloud Integration (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `provider_id` | path | mcn_provider_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_delete_provider_response](../schemas/mcn/mcn-delete-provider-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
