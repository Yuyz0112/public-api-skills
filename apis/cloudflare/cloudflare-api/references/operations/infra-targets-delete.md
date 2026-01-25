# DELETE /accounts/{account_id}/infrastructure/targets/{target_id}

**Resource:** [Infrastructure Access Targets](../resources/Infrastructure-Access-Targets.md)
**Delete target**
**Operation ID:** `infra-targets-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | infra_AccountTag | Yes |  |
| `target_id` | path | infra_TargetId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the target |
| 4XX | Failed to delete the target |

## Security

- **api_email**
- **api_key**
- **api_token**
