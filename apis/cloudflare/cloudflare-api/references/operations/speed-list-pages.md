# GET /zones/{zone_id}/speed_api/pages

**Resource:** [Observatory](../resources/Observatory.md)
**List tested webpages**
**Operation ID:** `speed-list-pages`

Lists all webpages which have been tested.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | observatory_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of pages. |
| 4XX | Failure response. |

**Success Response Schema:**

[observatory_pages-response-collection](../schemas/observatory/observatory-pages-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
