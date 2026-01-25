# PUT /accounts/{account_id}/profile

**Resource:** [Accounts](../resources/Accounts.md)
**Modify account profile**
**Operation ID:** `Accounts_modifyAccountProfile`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [organizations-api_Profile](../schemas/organizations-api/organizations-api-Profile.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | There is no content to send for this request, but the headers may be useful. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
