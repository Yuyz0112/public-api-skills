# POST /accounts/{account_id}/addressing/prefixes

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**Add Prefix**
**Operation ID:** `ip-address-management-prefixes-add-prefix`

Add a new prefix under the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add Prefix response |
| 4XX | Add Prefix response failure |

**Success Response Schema:**

[addressing_single_response](../schemas/addressing/addressing-single-response.md)

## Security

- **api_email**
- **api_key**
