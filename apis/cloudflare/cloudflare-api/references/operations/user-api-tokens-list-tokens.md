# GET /user/tokens

**Resource:** [User API Tokens](../resources/User-API-Tokens.md)
**List Tokens**
**Operation ID:** `user-api-tokens-list-tokens`

List all access tokens you created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `direction` | query | enum: asc, desc | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Tokens response |
| 4XX | List Tokens response failure |

**Success Response Schema:**

[iam_collection_tokens_response](../schemas/iam/iam-collection-tokens-response.md)

## Security

- **api_token**
