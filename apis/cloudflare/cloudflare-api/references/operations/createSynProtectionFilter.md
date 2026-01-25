# POST /accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Create a SYN Protection filter.**
**Operation ID:** `createSynProtectionFilter`

Create a SYN Protection filter for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Request Body

The new filter to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_NewExpressionFilter](../schemas/dos/dos-NewExpressionFilter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create SYN Protection filter response. |
| 4XX | Create SYN Protection filter failure. |

**Success Response Schema:**

[dos_expression-filter-response](../schemas/dos/dos-expression-filter-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
