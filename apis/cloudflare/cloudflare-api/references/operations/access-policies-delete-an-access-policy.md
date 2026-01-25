# DELETE /accounts/{account_id}/access/apps/{app_id}/policies/{policy_id}

**Resource:** [Access application-scoped policies](../resources/Access-application-scoped-policies.md)
**Delete an Access application policy**
**Operation ID:** `access-policies-delete-an-access-policy`

Deletes an Access policy specific to an application. To delete a reusable policy, use the /accounts/{account_id}/policies/{uid} endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes | The application ID. |
| `policy_id` | path | access_uuid | Yes | The policy ID. |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete an Access application policy response. |
| 4XX | Delete an Access application policy response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
