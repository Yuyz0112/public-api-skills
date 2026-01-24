# POST /v1/payment_method_configurations/{configuration}

**Resource:** [payment_method_configurations](../resources/payment-method-configurations.md)
**Update payment method configuration**
**Operation ID:** `PostPaymentMethodConfigurationsConfiguration`

<p>Update payment method configuration</p>

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

[payment_method_configuration](../schemas/payment/payment-method-configuration.md)

