# GET /zones/{zone_id}/speed_api/pages/{url}/tests

**Resource:** [Observatory](../resources/Observatory.md)
**List page test history**
**Operation ID:** `speed-list-test-history`

Test history (list of tests) for a specific webpage.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |
| `url` | path | observatory_url | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `region` | query | any | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of test history for a page. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_page-test-response-collection](../schemas/observatory/observatory-page-test-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
