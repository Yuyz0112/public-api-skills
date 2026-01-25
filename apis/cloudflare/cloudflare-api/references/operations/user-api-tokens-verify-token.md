# GET /user/tokens/verify

**Resource:** [User API Tokens](../resources/User-API-Tokens.md)
**Verify Token**
**Operation ID:** `user-api-tokens-verify-token`

Test whether a token works.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Verify Token response |
| 4XX | Verify Token response failure |

**Success Response Schema:**

[iam_token_verify_response_single_segment](../schemas/iam/iam-token-verify-response-single-segment.md)

## Security

- **api_token**
