# GET /accounts/{account_id}/magic/cloud/resources/{resource_id}

**Resource:** [Resources](../resources/Resources.md)
**Read Resource**
**Operation ID:** `resources-catalog-read`

Read an resource from the Resource Catalog (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `resource_id` | path | mcn_resource_id | Yes |  |
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

[mcn_read_account_resource_response](../schemas/mcn/mcn-read-account-resource-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
