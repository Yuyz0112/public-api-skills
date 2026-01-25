# GET /accounts/{account_id}/sso_connectors/{sso_connector_id}

**Resource:** [SSO](../resources/SSO.md)
**Get single SSO connector**
**Operation ID:** `get-sso-connector`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `sso_connector_id` | path | iam_sso_connector_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get SSO connector response |
| 4XX | Get SSO connector response failure |

**Success Response Schema:**

[iam_sso_connector_response](../schemas/iam/iam-sso-connector-response.md)

## Security

- **api_token**
