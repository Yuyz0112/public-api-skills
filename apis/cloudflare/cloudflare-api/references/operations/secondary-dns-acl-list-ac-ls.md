# GET /accounts/{account_id}/secondary_dns/acls

**Resource:** [Secondary DNS (ACL)](../resources/Secondary-DNS-ACL.md)
**List ACLs**
**Operation ID:** `secondary-dns-(-acl)-list-ac-ls`

List ACLs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List ACLs response. |
| 4XX | List ACLs response failure. |

**Success Response Schema:**

[secondary-dns_components-schemas-response_collection](../schemas/secondary-dns/secondary-dns-components-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
