# POST /accounts/{account_id}/addressing/prefixes/{prefix_id}/validate

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**Validate Prefix**
**Operation ID:** `ip-address-management-prefixes-validate-prefix`

Triggers a new prefix validation. The checks are run asynchronously and include IRR, RPKI, and prefix ownership.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Validate Prefix response |
| 4XX | Validate Prefix response failure |

## Security

- **api_email**
- **api_key**
