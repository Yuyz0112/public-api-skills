# GET /zones/{zone_id}/speed_api/availabilities

**Resource:** [Observatory](../resources/Observatory.md)
**Get quota and availability**
**Operation ID:** `speed-get-availabilities`

Retrieves quota for all plans, as well as the current zone quota.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Page test availability. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_availabilities-response](../schemas/observatory/observatory-availabilities-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
