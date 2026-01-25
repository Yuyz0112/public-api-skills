# GET /accounts/{account_id}/tokens/verify

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**Verify Token**
**Operation ID:** `account-api-tokens-verify-token`

Test whether a token works.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Verify Token response |
| 4XX | Verify Token response failure |

**Success Response Schema:**

[iam_token_verify_response_single_segment](../schemas/iam/iam-token-verify-response-single-segment.md)

## Security

- **api_token**
