# POST /zones/{zone_id}/logpush/validate/origin

**Resource:** [Logpush jobs for a zone](../resources/Logpush-jobs-for-a-zone.md)
**Validate origin**
**Operation ID:** `post-zones-zone_id-logpush-validate-origin`

Validates logpull origin with logpull_options.

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
| 200 | Validate origin response. |
| 4XX | Validate origin response failure. |

**Success Response Schema:**

[logpush_validate_response](../schemas/logpush/logpush-validate-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
