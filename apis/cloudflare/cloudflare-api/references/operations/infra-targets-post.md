# POST /accounts/{account_id}/infrastructure/targets

**Resource:** [Infrastructure Access Targets](../resources/Infrastructure-Access-Targets.md)
**Create new target**
**Operation ID:** `infra-targets-post`

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
| 200 | Successfully created the target |
| 4XX | Failed to create the target |

## Security

- **api_email**
- **api_key**
- **api_token**
