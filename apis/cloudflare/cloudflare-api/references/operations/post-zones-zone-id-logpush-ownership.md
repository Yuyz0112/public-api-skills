# POST /zones/{zone_id}/logpush/ownership

**Resource:** [Logpush jobs for a zone](../resources/Logpush-jobs-for-a-zone.md)
**Get ownership challenge**
**Operation ID:** `post-zones-zone_id-logpush-ownership`

Gets a new ownership challenge sent to your destination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logpush_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get ownership challenge response. |
| 4XX | Get ownership challenge response failure. |

**Success Response Schema:**

[logpush_get_ownership_response](../schemas/logpush/logpush-get-ownership-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
