# PUT /accounts/{account_id}/infrastructure/targets/batch

**Resource:** [Infrastructure Access Targets](../resources/Infrastructure-Access-Targets.md)
**Create new targets**
**Operation ID:** `infra-targets-put-batch`

Adds one or more targets.

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
| 200 | Successfully created the targets |
| 4XX | Failed to create the targets |

## Security

- **api_email**
- **api_key**
- **api_token**
