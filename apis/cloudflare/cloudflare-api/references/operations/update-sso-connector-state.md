# PATCH /accounts/{account_id}/sso_connectors/{sso_connector_id}

**Resource:** [SSO](../resources/SSO.md)
**Update SSO connector state**
**Operation ID:** `update-sso-connector-state`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `sso_connector_id` | path | iam_sso_connector_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update SSO connector state response |
| 4XX | Update SSO connector state response failure |

**Success Response Schema:**

[iam_sso_connector_response](../schemas/iam/iam-sso-connector-response.md)

## Security

- **api_token**
