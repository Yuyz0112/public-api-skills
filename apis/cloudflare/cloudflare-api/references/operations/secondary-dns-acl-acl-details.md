# GET /accounts/{account_id}/secondary_dns/acls/{acl_id}

**Resource:** [Secondary DNS (ACL)](../resources/Secondary-DNS-ACL.md)
**ACL Details**
**Operation ID:** `secondary-dns-(-acl)-acl-details`

Get ACL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `acl_id` | path | secondary-dns_components-schemas-identifier | Yes |  |
| `account_id` | path | secondary-dns_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | ACL Details response. |
| 4XX | ACL Details response failure. |

**Success Response Schema:**

[secondary-dns_components-schemas-single_response](../schemas/secondary-dns/secondary-dns-components-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
