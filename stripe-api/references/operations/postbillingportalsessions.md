# POST /v1/billing_portal/sessions

**Resource:** [billing_portal](../resources/billing-portal.md)
**Create a portal session**
**Operation ID:** `PostBillingPortalSessions`

<p>Creates a session of the customer portal.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing_portal.session](../schemas/billing/billing-portal-session.md)

