# GET /zones/{zone_id}/logs/rayids/{ray_id}

**Resource:** [Logs Received](../resources/Logs-Received.md)
**Get logs RayIDs**
**Operation ID:** `get-zones-zone_id-logs-rayids-ray_id`

The `/rayids` api route allows lookups by specific rayid. The rayids route will return zero, one, or more records (ray ids are not unique).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logshare_identifier | Yes |  |
| `ray_id` | path | logshare_ray_identifier | Yes |  |
| `fields` | query | logshare_fields | No |  |
| `timestamps` | query | logshare_timestamps | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get logs RayIDs response |
| 4XX | Get logs RayIDs response failure |

**Success Response Schema:**

[logshare_logs_response_json_lines](../schemas/logshare/logshare-logs-response-json-lines.md)

## Security

- **api_email**
- **api_key**
- **api_token**
