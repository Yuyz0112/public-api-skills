# POST /accounts/{account_id}/access/service_tokens

**Resource:** [Access service tokens](../resources/Access-service-tokens.md)
**Create a service token**
**Operation ID:** `access-service-tokens-create-a-service-token`

Generates a new service token. **Note:** This is the only time you can get the Client Secret. If you lose the Client Secret, you will have to rotate the Client Secret or create a new service token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create a service token response |
| 4XX | Create a service token response failure |

**Success Response Schema:**

[access_create_response](../schemas/access/access-create-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
