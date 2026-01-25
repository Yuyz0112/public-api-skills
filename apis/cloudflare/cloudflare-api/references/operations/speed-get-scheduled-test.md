# GET /zones/{zone_id}/speed_api/schedule/{url}

**Resource:** [Observatory](../resources/Observatory.md)
**Get a page test schedule**
**Operation ID:** `speed-get-scheduled-test`

Retrieves the test schedule for a page in a specific region.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |
| `url` | path | observatory_url | Yes |  |
| `region` | query | any | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Page test schedule. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_schedule-response-single](../schemas/observatory/observatory-schedule-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
