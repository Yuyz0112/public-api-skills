# POST /accounts/{account_id}/secondary_dns/acls

**Resource:** [Secondary DNS (ACL)](../resources/Secondary-DNS-ACL.md)
**Create ACL**
**Operation ID:** `secondary-dns-(-acl)-create-acl`

Create ACL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create ACL response. |
| 4XX | Create ACL response failure. |

**Success Response Schema:**

[secondary-dns_components-schemas-single_response](../schemas/secondary-dns/secondary-dns-components-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
