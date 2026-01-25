# GET /zones/{zone_id}/hold

**Resource:** [Zone Holds](../resources/Zone-Holds.md)
**Get Zone Hold**
**Operation ID:** `zones-0-hold-get`

Retrieve whether the zone is subject to a zone hold, and metadata about the hold.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_schemas-identifier | Yes | Zone ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |
| 4XX | Client Error |

## Security

- **api_token**
- **api_email**
- **api_key**
