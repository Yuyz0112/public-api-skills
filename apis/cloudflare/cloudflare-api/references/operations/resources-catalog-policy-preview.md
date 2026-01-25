# POST /accounts/{account_id}/magic/cloud/resources/policy-preview

**Resource:** [Resources](../resources/Resources.md)
**Preview Rego Query**
**Operation ID:** `resources-catalog-policy-preview`

Preview Rego query result against the latest resource catalog (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mcn_resources_catalog_policy_preview_request](../schemas/mcn/mcn-resources-catalog-policy-preview-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 422 | Unprocessable Entity. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_resources_catalog_policy_preview_response](../schemas/mcn/mcn-resources-catalog-policy-preview-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
