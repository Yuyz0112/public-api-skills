# POST /zones/{zone_id}/speed_api/pages/{url}/tests

**Resource:** [Observatory](../resources/Observatory.md)
**Start page test**
**Operation ID:** `speed-create-test`

Starts a test for a specific webpage, in a specific region.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |
| `url` | path | observatory_url | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Page test details. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_page-test-response-single](../schemas/observatory/observatory-page-test-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
