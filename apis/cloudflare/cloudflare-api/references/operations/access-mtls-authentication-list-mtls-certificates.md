# GET /accounts/{account_id}/access/certificates

**Resource:** [Access mTLS authentication](../resources/Access-mTLS-authentication.md)
**List mTLS certificates**
**Operation ID:** `access-mtls-authentication-list-mtls-certificates`

Lists all mTLS root certificates.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List mTLS certificates response |
| 4XX | List mTLS certificates response failure |

**Success Response Schema:**

[access_certificates_components-schemas-response_collection](../schemas/access/access-certificates-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
