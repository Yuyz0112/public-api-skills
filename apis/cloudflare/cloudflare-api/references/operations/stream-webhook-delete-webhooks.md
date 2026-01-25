# DELETE /accounts/{account_id}/stream/webhook

**Resource:** [Stream Webhook](../resources/Stream-Webhook.md)
**Delete webhooks**
**Operation ID:** `stream-webhook-delete-webhooks`

Deletes a webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete webhooks response. |
| 4XX | Delete webhooks response failure. |

**Success Response Schema:**

[stream_deleted_response](../schemas/stream/stream-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
