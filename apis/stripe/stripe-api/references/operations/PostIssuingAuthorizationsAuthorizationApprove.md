# POST /v1/issuing/authorizations/{authorization}/approve

**Resource:** [issuing](../resources/issuing.md)
**Approve an authorization**
**Operation ID:** `PostIssuingAuthorizationsAuthorizationApprove`
⚠️ **Deprecated**

<p>[Deprecated] Approves a pending Issuing <code>Authorization</code> object. This request should be made within the timeout window of the <a href="/docs/issuing/controls/real-time-authorizations">real-time authorization</a> flow. 
This method is deprecated. Instead, <a href="/docs/issuing/controls/real-time-authorizations#authorization-handling">respond directly to the webhook request to approve an authorization</a>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `authorization` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.authorization](../schemas/issuing-authorization/issuing-authorization.md)

