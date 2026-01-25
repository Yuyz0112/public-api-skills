# POST /accounts/{account_id}/diagnostics/traceroute

**Resource:** [Diagnostics](../resources/Diagnostics.md)
**Traceroute**
**Operation ID:** `diagnostics-traceroute`

Run traceroutes from Cloudflare colos.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-transit_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Traceroute response. |
| 4XX | Traceroute response failure. |

**Success Response Schema:**

[magic-transit_traceroute_response_collection](../schemas/magic-transit/magic-transit-traceroute-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
