# GET /accounts/{account_id}/cloudforce-one/events/{event_id}/relationships

**Resource:** [Event](../resources/Event.md)
**Filter and list events related to specific event**
**Operation ID:** `get_EventRelationships`

The `event_id` must be defined (to list existing events (and their IDs), use the [`Filter and List Events`](https://developers.cloudflare.com/api/resources/cloudforce_one/subresources/threat_events/methods/list/) endpoint). Also, must provide query parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event UUID. |
| `direction` | query | enum: ancestors, descendants, both | No | The direction to traverse the graph. Defaults to 'both' to search all. |
| `maxDepth` | query | number | No | The maximum depth to traverse. Defaults to 5. |
| `relationshipTypes` | query | any | No | An optional array of relationship types to filter by. |
| `indicatorTypeIds` | query | string[] | No | An optional array of indicator type IDs to filter the results by. |
| `datasetId` | query | string | Yes | The dataset ID to search within. |
| `includeParent` | query | boolean | No | Whether to include the starting event in the results. Defaults to true. |
| `page` | query | number | No |  |
| `pageSize` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of events related to the specified starting event. |
| 400 | Bad Request. |

## Security

- **api_token**
