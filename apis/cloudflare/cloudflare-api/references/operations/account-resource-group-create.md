# POST /accounts/{account_id}/iam/resource_groups

**Resource:** [Account Resource Groups](../resources/Account-Resource-Groups.md)
**Create Resource Group**
**Operation ID:** `account-resource-group-create`

Create a new Resource Group under the specified account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_request_create_resource_group](../schemas/iam/iam-request-create-resource-group.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add Resource Group response |
| 4XX | Add Resource Group response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
