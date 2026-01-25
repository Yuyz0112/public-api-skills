# POST /zones/{zone_id}/logpush/ownership/validate

**Resource:** [Logpush jobs for a zone](../resources/Logpush-jobs-for-a-zone.md)
**Validate ownership challenge**
**Operation ID:** `post-zones-zone_id-logpush-ownership-validate`

Validates ownership challenge of the destination.

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
| 200 | Validate ownership challenge response. |
| 4XX | Validate ownership challenge response failure. |

**Success Response Schema:**

[logpush_validate_ownership_response](../schemas/logpush/logpush-validate-ownership-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
