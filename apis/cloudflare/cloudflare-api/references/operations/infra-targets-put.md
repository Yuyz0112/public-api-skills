# PUT /accounts/{account_id}/infrastructure/targets/{target_id}

**Resource:** [Infrastructure Access Targets](../resources/Infrastructure-Access-Targets.md)
**Update target**
**Operation ID:** `infra-targets-put`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | infra_AccountTag | Yes |  |
| `target_id` | path | infra_TargetId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the target |
| 4XX | Failed to update the target |

## Security

- **api_email**
- **api_key**
- **api_token**
