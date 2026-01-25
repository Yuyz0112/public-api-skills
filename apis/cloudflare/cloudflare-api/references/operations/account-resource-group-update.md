# PUT /accounts/{account_id}/iam/resource_groups/{resource_group_id}

**Resource:** [Account Resource Groups](../resources/Account-Resource-Groups.md)
**Update Resource Group**
**Operation ID:** `account-resource-group-update`

Modify an existing resource group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `resource_group_id` | path | iam_resource_group_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_request_update_resource_group](../schemas/iam/iam-request-update-resource-group.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Resource Group response |
| 4XX | Update Resource Group response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
