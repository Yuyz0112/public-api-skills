# GET /oncalls

**Resource:** [On-Calls](../resources/On-Calls.md)
**List all of the on-calls**
**Operation ID:** `listOnCalls`

List the on-call entries during a given time range.

An on-call represents a contiguous unit of time for which a User will be on call for a given Escalation Policy and Escalation Rules.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#on-calls)

Scoped OAuth requires: `oncalls.read`

This API operation has operation specific rate limits. See the [Rate Limits](https://developer.pagerduty.com/docs/72d3b724589e3-rest-api-rate-limits) page for more information.


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of on-call objects. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

