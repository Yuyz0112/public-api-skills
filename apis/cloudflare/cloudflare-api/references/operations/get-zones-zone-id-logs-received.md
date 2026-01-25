# GET /zones/{zone_id}/logs/received

**Resource:** [Logs Received](../resources/Logs-Received.md)
**Get logs received**
**Operation ID:** `get-zones-zone_id-logs-received`

The `/received` api route allows customers to retrieve their edge HTTP logs. The basic access pattern is "give me all the logs for zone Z for minute M", where the minute M refers to the time records were received at Cloudflare's central data center. `start` is inclusive, and `end` is exclusive. Because of that, to get all data, at minutely cadence, starting at 10AM, the proper values are: `start=2018-05-20T10:00:00Z&end=2018-05-20T10:01:00Z`, then `start=2018-05-20T10:01:00Z&end=2018-05-20T10:02:00Z` and so on; the overlap will be handled properly.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logshare_identifier | Yes |  |
| `start` | query | logshare_start | No |  |
| `end` | query | logshare_end | Yes |  |
| `fields` | query | logshare_fields | No |  |
| `sample` | query | logshare_sample | No |  |
| `count` | query | logshare_count | No |  |
| `timestamps` | query | logshare_timestamps | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get logs received response |
| 4XX | Get logs received response failure |

**Success Response Schema:**

[logshare_logs_response_json_lines](../schemas/logshare/logshare-logs-response-json-lines.md)

## Security

- **api_email**
- **api_key**
- **api_token**
