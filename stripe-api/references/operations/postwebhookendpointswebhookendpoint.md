# POST /v1/webhook_endpoints/{webhook_endpoint}

**Resource:** [webhook_endpoints](../resources/webhook-endpoints.md)
**Update a webhook endpoint**
**Operation ID:** `PostWebhookEndpointsWebhookEndpoint`

<p>Updates the webhook endpoint. You may edit the <code>url</code>, the list of <code>enabled_events</code>, and the status of your endpoint.</p>

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

[webhook_endpoint](../schemas/webhook/webhook-endpoint.md)

