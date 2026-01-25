# DELETE /accounts/{account_id}/sso_connectors/{sso_connector_id}

**Resource:** [SSO](../resources/SSO.md)
**Delete SSO connector**
**Operation ID:** `delete-sso-connector`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `sso_connector_id` | path | iam_sso_connector_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete SSO connector response |
| 4XX | Delete SSO connector response failure |

**Success Response Schema:**

[iam_api-response-single-id](../schemas/iam/iam-api-response-single-id.md)

## Security

- **api_token**
