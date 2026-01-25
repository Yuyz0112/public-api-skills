# GET /zones/{zone_id}/settings/ssl_automatic_mode

**Resource:** [Automatic SSL/TLS](../resources/Automatic-SSL-TLS.md)
**Get Automatic SSL/TLS enrollment status for the given zone**
**Operation ID:** `ssl-detector-automatic-mode-get-enrollment`

If the system is enabled, the response will include next_scheduled_scan, representing the next time this zone will be scanned and the zone's ssl/tls encryption mode is potentially upgraded by the system. If the system is disabled, next_scheduled_scan will not be present in the response body.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Automatic SSL/TLS Enrollment status response. |
| 4XX | Get Automatic SSL/TLS Enrollment status failure. |

**Success Response Schema:**

[cache_api-response-single-id](../schemas/cache/cache-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
