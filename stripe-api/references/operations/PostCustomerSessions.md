# POST /v1/customer_sessions

**Resource:** [customer_sessions](../resources/customer-sessions.md)
**Create a Customer Session**
**Operation ID:** `PostCustomerSessions`

<p>Creates a Customer Session object that includes a single-use client secret that you can use on your front-end to grant client-side API access for certain customer resources.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[customer_session](../schemas/customer/customer-session.md)

