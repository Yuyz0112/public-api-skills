# POST /accounts/{account_id}/cloudforce-one/events/{dataset_id}/revert-do

**Resource:** [Event](../resources/Event.md)
**Revert an Events Durable Object to a point in time**
**Operation ID:** `post_EventDoRevert`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Revert scheduled for the specified Durable Object. |
| 400 | Bad Request. |

## Security

- **api_token**
