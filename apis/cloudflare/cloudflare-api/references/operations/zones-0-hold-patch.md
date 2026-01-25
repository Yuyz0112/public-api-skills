# PATCH /zones/{zone_id}/hold

**Resource:** [Zone Holds](../resources/Zone-Holds.md)
**Update Zone Hold**
**Operation ID:** `zones-0-hold-patch`

Update the `hold_after` and/or `include_subdomains` values on an existing zone hold.
The hold is enabled if the `hold_after` date-time value is in the past.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_schemas-identifier | Yes | Zone ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |
| 4XX | Client Error |

## Security

- **api_token**
- **api_email**
- **api_key**
