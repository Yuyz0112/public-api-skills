# GET /zones/{zone_id}/speed_api/pages/{url}/tests/{test_id}

**Resource:** [Observatory](../resources/Observatory.md)
**Get a page test result**
**Operation ID:** `speed-get-test`

Retrieves the result of a specific test.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |
| `url` | path | observatory_url | Yes |  |
| `test_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Page test result. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_page-test-response-single](../schemas/observatory/observatory-page-test-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
