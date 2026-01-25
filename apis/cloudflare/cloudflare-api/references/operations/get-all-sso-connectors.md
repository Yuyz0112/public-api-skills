# GET /accounts/{account_id}/sso_connectors

**Resource:** [SSO](../resources/SSO.md)
**Get all SSO connectors**
**Operation ID:** `get-all-sso-connectors`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get all SSO connectors response |
| 4XX | Get all SSO connectors response failure |

**Success Response Schema:**

[iam_sso_connector_collection_response](../schemas/iam/iam-sso-connector-collection-response.md)

## Security

- **api_token**
