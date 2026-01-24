# DELETE /v1/apple_pay/domains/{domain}

**Resource:** [apple_pay](../resources/apple-pay.md)
**Operation ID:** `DeleteApplePayDomainsDomain`

<p>Delete an apple pay domain.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_apple_pay_domain](../schemas/deleted/deleted-apple-pay-domain.md)

