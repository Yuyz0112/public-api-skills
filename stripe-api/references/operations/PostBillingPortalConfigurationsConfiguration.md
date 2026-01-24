# POST /v1/billing_portal/configurations/{configuration}

**Resource:** [billing_portal](../resources/billing-portal.md)
**Update a portal configuration**
**Operation ID:** `PostBillingPortalConfigurationsConfiguration`

<p>Updates a configuration that describes the functionality of the customer portal.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `configuration` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing_portal.configuration](../schemas/billing/billing-portal-configuration.md)

