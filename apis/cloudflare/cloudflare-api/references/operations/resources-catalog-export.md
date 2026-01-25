# GET /accounts/{account_id}/magic/cloud/resources/export

**Resource:** [Resources](../resources/Resources.md)
**Export Resources**
**Operation ID:** `resources-catalog-export`

Export resources in the Resource Catalog as a JSON file (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `provider_id` | query | string | No |  |
| `resource_type` | query | mcn_resource_type[] | No |  |
| `resource_id` | query | mcn_resource_id[] | No |  |
| `region` | query | string | No |  |
| `resource_group` | query | string | No |  |
| `search` | query | string[] | No |  |
| `order_by` | query | string | No | One of ["id", "resource_type", "region"]. |
| `desc` | query | boolean | No |  |
| `v2` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Exported file. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 500 | Internal Server Error. |

## Security

- **api_email**
- **api_key**
- **api_token**
