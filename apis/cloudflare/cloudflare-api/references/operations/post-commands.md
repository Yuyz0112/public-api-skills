# POST /accounts/{account_id}/dex/commands

**Resource:** [DEX Remote Commands](../resources/DEX-Remote-Commands.md)
**Create account commands**
**Operation ID:** `post-commands`

Initiate commands for up to 10 devices per account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create commands response |
| 4XX | Create commands failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
