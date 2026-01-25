# POST /zones/{zone_id}/logpush/validate/destination

**Resource:** [Logpush jobs for a zone](../resources/Logpush-jobs-for-a-zone.md)
**Validate destination**
**Operation ID:** `post-zones-zone_id-logpush-validate-destination`

Validates destination.

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
| 200 | Validate destination response. |
| 4XX | Validate destination response failure. |

**Success Response Schema:**

[logpush_validate_response](../schemas/logpush/logpush-validate-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
