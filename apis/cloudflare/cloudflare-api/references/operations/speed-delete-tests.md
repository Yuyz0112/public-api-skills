# DELETE /zones/{zone_id}/speed_api/pages/{url}/tests

**Resource:** [Observatory](../resources/Observatory.md)
**Delete all page tests**
**Operation ID:** `speed-delete-tests`

Deletes all tests for a specific webpage from a specific region. Deleted tests are still counted as part of the quota.

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
