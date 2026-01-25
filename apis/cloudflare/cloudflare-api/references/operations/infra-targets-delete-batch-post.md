# POST /accounts/{account_id}/infrastructure/targets/batch_delete

**Resource:** [Infrastructure Access Targets](../resources/Infrastructure-Access-Targets.md)
**Delete targets**
**Operation ID:** `infra-targets-delete-batch-post`

Removes one or more targets.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | infra_AccountTag | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the targets |
| 4XX | Failed to delete the targets |

## Security

- **api_email**
- **api_key**
- **api_token**
