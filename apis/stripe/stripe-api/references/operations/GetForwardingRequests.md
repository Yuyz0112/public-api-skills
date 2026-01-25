# GET /v1/forwarding/requests

**Resource:** [forwarding](../resources/forwarding.md)
**List all ForwardingRequests**
**Operation ID:** `GetForwardingRequests`

<p>Lists all ForwardingRequest objects.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created` | query | object | No | Similar to other List endpoints, filters results based on created timestamp. You can pass gt, gte, lt, and lte timestamp values. |
| `ending_before` | query | string | No | A pagination cursor to fetch the previous page of the list. The value must be a ForwardingRequest ID. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A pagination cursor to fetch the next page of the list. The value must be a ForwardingRequest ID. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

