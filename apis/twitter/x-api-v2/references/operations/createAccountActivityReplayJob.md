# POST /2/account_activity/replay/webhooks/{webhook_id}/subscriptions/all

**Resource:** [Account Activity](../resources/Account-Activity.md)
**Create replay job**
**Operation ID:** `createAccountActivityReplayJob`

Creates a replay job to retrieve activities from up to the past 5 days for all subscriptions associated with a given webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The unique identifier for the webhook configuration. |
| `from_date` | query | string | Yes | The oldest (starting) UTC timestamp (inclusive) from which events will be provided, in `yyyymmddhhmm` format. |
| `to_date` | query | string | Yes | The latest (ending) UTC timestamp (exclusive) up to which events will be provided, in `yyyymmddhhmm` format. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ReplayJobCreateResponse](../schemas/Replay/ReplayJobCreateResponse.md)

## Security

- **BearerToken**
