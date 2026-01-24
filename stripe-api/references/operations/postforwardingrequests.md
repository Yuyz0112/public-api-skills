# POST /v1/forwarding/requests

**Resource:** [forwarding](../resources/forwarding.md)
**Create a ForwardingRequest**
**Operation ID:** `PostForwardingRequests`

<p>Creates a ForwardingRequest object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[forwarding.request](../schemas/forwarding-request/forwarding-request.md)

