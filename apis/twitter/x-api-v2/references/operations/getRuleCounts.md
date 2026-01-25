# GET /2/tweets/search/stream/rules/counts

**Resource:** [Stream](../resources/Stream.md)
**Get stream rule counts**
**Operation ID:** `getRuleCounts`

Retrieves the count of rules in the active rule set for the filtered stream.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2TweetsSearchStreamRulesCountsResponse](../schemas/Get/Get2TweetsSearchStreamRulesCountsResponse.md)

## Security

- **BearerToken**
