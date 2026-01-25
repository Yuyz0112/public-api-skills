# PUT /accounts/{account_id}/secondary_dns/acls/{acl_id}

**Resource:** [Secondary DNS (ACL)](../resources/Secondary-DNS-ACL.md)
**Update ACL**
**Operation ID:** `secondary-dns-(-acl)-update-acl`

Modify ACL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `acl_id` | path | secondary-dns_components-schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [secondary-dns_acl](../schemas/secondary-dns/secondary-dns-acl.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update ACL response. |
| 4XX | Update ACL response failure. |

**Success Response Schema:**

[secondary-dns_components-schemas-single_response](../schemas/secondary-dns/secondary-dns-components-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
