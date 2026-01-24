# GET /v1/webhook_endpoints/{webhook_endpoint}

**Resource:** [webhook_endpoints](../resources/webhook-endpoints.md)
**Retrieve a webhook endpoint**
**Operation ID:** `GetWebhookEndpointsWebhookEndpoint`

<p>Retrieves the webhook endpoint with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

