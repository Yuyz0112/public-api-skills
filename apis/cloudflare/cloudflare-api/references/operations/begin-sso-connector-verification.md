# POST /accounts/{account_id}/sso_connectors/{sso_connector_id}/begin_verification

**Resource:** [SSO](../resources/SSO.md)
**Begin SSO connector verification**
**Operation ID:** `begin-sso-connector-verification`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `sso_connector_id` | path | iam_sso_connector_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Begin SSO connector verification process response |
| 4XX | Begin SSO connector verification process response failure |

**Success Response Schema:**

[iam_api-response-single](../schemas/iam/iam-api-response-single.md)

## Security

- **api_token**
