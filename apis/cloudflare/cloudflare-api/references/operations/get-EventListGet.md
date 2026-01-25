# GET /accounts/{account_id}/cloudforce-one/events

**Resource:** [Event](../resources/Event.md)
**Filter and list events**
**Operation ID:** `get_EventListGet`

When `datasetId` is unspecified, events will be listed from the `Cloudforce One Threat Events` dataset. To list existing datasets (and their IDs), use the [`List Datasets`](https://developers.cloudflare.com/api/resources/cloudforce_one/subresources/threat_events/subresources/datasets/methods/list/) endpoint). Also, must provide query parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `search` | query | object[] | No |  |
| `page` | query | number | No |  |
| `pageSize` | query | number | No |  |
| `orderBy` | query | string | No |  |
| `order` | query | enum: asc, desc | No |  |
| `datasetId` | query | string[] | No |  |
| `forceRefresh` | query | boolean | No |  |
| `format` | query | enum: json, stix2 | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of events. |
| 400 | Bad Request. |

## Security

- **api_token**
