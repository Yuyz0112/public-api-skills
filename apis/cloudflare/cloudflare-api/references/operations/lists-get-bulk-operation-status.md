# GET /accounts/{account_id}/rules/lists/bulk_operations/{operation_id}

**Resource:** [Lists](../resources/Lists.md)
**Get bulk operation status**
**Operation ID:** `lists-get-bulk-operation-status`

Gets the current status of an asynchronous operation on a list.

The `status` property can have one of the following values: `pending`, `running`, `completed`, or `failed`. If the status is `failed`, the `error` property will contain a message describing the error.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `operation_id` | path | lists_operation_id | Yes |  |
| `account_id` | path | lists_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get bulk operation status response. |
| 4XX | Get bulk operation status response failure. |

**Success Response Schema:**

[lists_bulk-operation-response-single](../schemas/lists/lists-bulk-operation-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
