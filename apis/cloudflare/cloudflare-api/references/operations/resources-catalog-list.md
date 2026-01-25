# GET /accounts/{account_id}/magic/cloud/resources

**Resource:** [Resources](../resources/Resources.md)
**List Resources**
**Operation ID:** `resources-catalog-list`

List resources in the Resource Catalog (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `provider_id` | query | string | No |  |
| `resource_type` | query | mcn_resource_type[] | No |  |
| `resource_id` | query | mcn_resource_id[] | No |  |
| `region` | query | string | No |  |
| `resource_group` | query | string | No |  |
| `managed` | query | boolean | No |  |
| `search` | query | string[] | No |  |
| `order_by` | query | string | No | One of ["id", "resource_type", "region"]. |
| `desc` | query | boolean | No |  |
| `per_page` | query | integer | No |  |
| `page` | query | integer | No |  |
| `cloudflare` | query | boolean | No |  |
| `v2` | query | boolean | No |  |

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

[mcn_read_account_resources_response](../schemas/mcn/mcn-read-account-resources-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
