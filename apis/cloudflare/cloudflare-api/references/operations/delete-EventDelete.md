# DELETE /accounts/{account_id}/cloudforce-one/events/{event_id}

**Resource:** [Event](../resources/Event.md)
**Deletes an event**
**Operation ID:** `delete_EventDelete`

The `datasetId` parameter must be defined. To list existing datasets (and their IDs) in your account, use the [`List Datasets`](https://developers.cloudflare.com/api/resources/cloudforce_one/subresources/threat_events/subresources/datasets/methods/list/) endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the uuid of the deleted event. |
| 400 | Bad Request. |

## Security

- **api_token**
