# PUT /user/tokens/{token_id}/value

**Resource:** [User API Tokens](../resources/User-API-Tokens.md)
**Roll Token**
**Operation ID:** `user-api-tokens-roll-token`

Roll the token secret.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token_id` | path | iam_token_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Roll Token response |
| 4XX | Roll Token response failure |

**Success Response Schema:**

[iam_response_single_value](../schemas/iam/iam-response-single-value.md)

## Security

- **api_token**
