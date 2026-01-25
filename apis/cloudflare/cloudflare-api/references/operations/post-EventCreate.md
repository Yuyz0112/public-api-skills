# POST /accounts/{account_id}/cloudforce-one/events/create

**Resource:** [Event](../resources/Event.md)
**Creates a new event**
**Operation ID:** `post_EventCreate`

To create a dataset, see the [`Create Dataset`](https://developers.cloudflare.com/api/resources/cloudforce_one/subresources/threat_events/subresources/datasets/methods/create/) endpoint. When `datasetId` parameter is unspecified, it will be created in a default dataset named `Cloudforce One Threat Events`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created event. |
| 400 | Bad Request. |

## Security

- **api_token**
