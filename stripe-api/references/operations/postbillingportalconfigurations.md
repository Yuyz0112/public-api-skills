# POST /v1/billing_portal/configurations

**Resource:** [billing_portal](../resources/billing-portal.md)
**Create a portal configuration**
**Operation ID:** `PostBillingPortalConfigurations`

<p>Creates a configuration that describes the functionality and behavior of a PortalSession</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing_portal.configuration](../schemas/billing/billing-portal-configuration.md)

