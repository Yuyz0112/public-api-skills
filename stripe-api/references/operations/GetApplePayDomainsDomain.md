# GET /v1/apple_pay/domains/{domain}

**Resource:** [apple_pay](../resources/apple-pay.md)
**Operation ID:** `GetApplePayDomainsDomain`

<p>Retrieve an apple pay domain.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[apple_pay_domain](../schemas/apple/apple-pay-domain.md)

