# DELETE /zones/{zone_id}/speed_api/schedule/{url}

**Resource:** [Observatory](../resources/Observatory.md)
**Delete scheduled page test**
**Operation ID:** `speed-delete-test-schedule`

Deletes a scheduled test for a page.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |
| `url` | path | observatory_url | Yes |  |
| `region` | query | any | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Number of deleted tests. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_count-response](../schemas/observatory/observatory-count-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
