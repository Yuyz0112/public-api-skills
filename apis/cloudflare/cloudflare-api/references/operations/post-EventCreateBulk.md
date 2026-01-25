# POST /accounts/{account_id}/cloudforce-one/events/create/bulk

**Resource:** [Event](../resources/Event.md)
**Creates bulk events**
**Operation ID:** `post_EventCreateBulk`

The `datasetId` parameter must be defined. To list existing datasets (and their IDs) in your account, use the [`List Datasets`](https://developers.cloudflare.com/api/resources/cloudforce_one/subresources/threat_events/subresources/datasets/methods/list/) endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted. Events created; indicators queued for async processing. |
| 400 | Bad Request. |

## Security

- **api_token**
