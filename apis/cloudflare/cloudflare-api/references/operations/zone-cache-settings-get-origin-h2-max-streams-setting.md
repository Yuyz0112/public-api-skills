# GET /zones/{zone_id}/settings/origin_h2_max_streams

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Get Origin H2 Max Streams Setting**
**Operation ID:** `zone-cache-settings-get-origin-h2-max-streams-setting`

Origin H2 Max Streams configures the max number of concurrent requests that Cloudflare will send within the same connection when communicating with the origin server, if the origin supports it. Note that if your origin does not support H2 multiplexing, 5xx errors may be observed, particularly 520s. Also note that the default value is `100` for all plan types except Enterprise where it is `1`. `1` means that H2 multiplexing is disabled.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Origin H2 Max Streams setting response. |
| 4XX | Get Origin H2 Max Streams setting response failure. |

**Success Response Schema:**

[cache-rules_origin_h2_max_streams_response_value](../schemas/cache-rules/cache-rules-origin-h2-max-streams-response-value.md)

## Security

- **api_token**
- **api_email**
- **api_key**
