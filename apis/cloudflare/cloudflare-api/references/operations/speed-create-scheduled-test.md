# POST /zones/{zone_id}/speed_api/schedule/{url}

**Resource:** [Observatory](../resources/Observatory.md)
**Create scheduled page test**
**Operation ID:** `speed-create-scheduled-test`

Creates a scheduled test for a page.

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

[observatory_create-schedule-response](../schemas/observatory/observatory-create-schedule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
