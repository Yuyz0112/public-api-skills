# PATCH /accounts/{account_id}/addressing/prefixes/{prefix_id}

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**Update Prefix Description**
**Operation ID:** `ip-address-management-prefixes-update-prefix-description`

Modify the description for a prefix owned by the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Prefix Description response |
| 4XX | Update Prefix Description response failure |

**Success Response Schema:**

[addressing_single_response](../schemas/addressing/addressing-single-response.md)

## Security

- **api_email**
- **api_key**
