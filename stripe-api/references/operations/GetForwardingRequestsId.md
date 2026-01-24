# GET /v1/forwarding/requests/{id}

**Resource:** [forwarding](../resources/forwarding.md)
**Retrieve a ForwardingRequest**
**Operation ID:** `GetForwardingRequestsId`

<p>Retrieves a ForwardingRequest object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[forwarding.request](../schemas/forwarding-request/forwarding-request.md)

