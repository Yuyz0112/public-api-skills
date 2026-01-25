# POST /accounts/{account_id}/sso_connectors

**Resource:** [SSO](../resources/SSO.md)
**Initialize new SSO connector**
**Operation ID:** `init-new-sso-connector`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Initialize new SSO connector response |
| 4XX | Initialize new SSO connector response failure |

**Success Response Schema:**

[iam_sso_connector_response](../schemas/iam/iam-sso-connector-response.md)

## Security

- **api_token**
