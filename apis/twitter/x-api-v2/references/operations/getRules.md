# GET /2/tweets/search/stream/rules

**Resource:** [Stream](../resources/Stream.md)
**Get stream rules**
**Operation ID:** `getRules`

Retrieves the active rule set or a subset of rules for the filtered stream.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | RuleId[] | No | A comma-separated list of Rule IDs. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | string | No | This value is populated by passing the 'next_token' returned in a request to paginate through results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[RulesLookupResponse](../schemas/Rules/RulesLookupResponse.md)

## Security

- **BearerToken**
