# PATCH /zones/{zone_id}/settings/ssl_automatic_mode

**Resource:** [Automatic SSL/TLS](../resources/Automatic-SSL-TLS.md)
**Patch Automatic SSL/TLS Enrollment status for given zone**
**Operation ID:** `ssl-detector-automatic-mode-patch-enrollment`

The automatic system is enabled when this endpoint is hit with value in the request body is set to "auto", and disabled when the request body value is set to "custom".

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cache_schemas_patch](../schemas/cache/cache-schemas-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Automatic SSL/TLS Enrollment status response. |
| 4XX | Patch Automatic SSL/TLS Enrollment status failure. |

**Success Response Schema:**

[cache_api-response-single-id](../schemas/cache/cache-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
