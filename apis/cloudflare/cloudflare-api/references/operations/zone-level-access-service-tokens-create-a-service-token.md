# POST /zones/{zone_id}/access/service_tokens

**Resource:** [Zone-Level Access service tokens](../resources/Zone-Level-Access-service-tokens.md)
**Create a service token**
**Operation ID:** `zone-level-access-service-tokens-create-a-service-token`

Generates a new service token. **Note:** This is the only time you can get the Client Secret. If you lose the Client Secret, you will have to create a new service token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create a service token response |
| 4XX | Create a service token response failure |

**Success Response Schema:**

[access_schemas-create_response](../schemas/access/access-schemas-create-response.md)

## Security

- **api_email**
- **api_key**
