# DELETE /v1/webhook_endpoints/{webhook_endpoint}

**Resource:** [webhook_endpoints](../resources/webhook-endpoints.md)
**Delete a webhook endpoint**
**Operation ID:** `DeleteWebhookEndpointsWebhookEndpoint`

<p>You can also delete webhook endpoints via the <a href="https://dashboard.stripe.com/account/webhooks">webhook endpoint management</a> page of the Stripe dashboard.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_endpoint` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_webhook_endpoint](../schemas/deleted/deleted-webhook-endpoint.md)

