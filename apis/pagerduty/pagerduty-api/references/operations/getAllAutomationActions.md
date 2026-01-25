# GET /automation_actions/actions

**Resource:** [Automation Actions](../resources/Automation-Actions.md)
**List Automation Actions**
**Operation ID:** `getAllAutomationActions`

Lists Automation Actions matching provided query params.

The returned records are sorted by action name in alphabetical order.

See [`Cursor-based pagination`](https://developer.pagerduty.com/docs/rest-api-v2/pagination/) for instructions on how to paginate through the result set.


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of actions |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

