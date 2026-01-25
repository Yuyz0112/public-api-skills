# GET /accounts/{account_id}/access/certificates/settings

**Resource:** [Access mTLS authentication](../resources/Access-mTLS-authentication.md)
**List all mTLS hostname settings**
**Operation ID:** `access-mtls-authentication-list-mtls-certificates-hostname-settings`

List all mTLS hostname settings for this account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List mTLS hostname settings response |
| 4XX | List mTLS hostname settings response failure |

**Success Response Schema:**

[access_response_collection_hostnames](../schemas/access/access-response-collection-hostnames.md)

## Security

- **api_email**
- **api_key**
- **api_token**
