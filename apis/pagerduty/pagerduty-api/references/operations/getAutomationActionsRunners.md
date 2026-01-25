# GET /automation_actions/runners

**Resource:** [Automation Actions](../resources/Automation-Actions.md)
**List Automation Action runners**
**Operation ID:** `getAutomationActionsRunners`

Lists Automation Action runners matching provided query params.
The returned records are sorted by runner name in alphabetical order.

See [`Cursor-based pagination`](https://developer.pagerduty.com/docs/rest-api-v2/pagination/) for instructions on how to paginate through the result set.


## Responses

| Status | Description |
|--------|-------------|
| 200 | Runners matching the criteria. |
| 401 | (reference) |
| 402 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

