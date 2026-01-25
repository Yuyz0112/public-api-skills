# POST /accounts/{account_id}/workers/observability/telemetry/keys

**Resource:** [Keys](../resources/Keys.md)
**List keys**
**Operation ID:** `telemetry.keys.list`

List all the keys in your telemetry events.

## Request Body

Find keys in your telemetry events, matching a specific filter or needle.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful request |
| 401 | Unauthorized |
| 500 | Internal error |

