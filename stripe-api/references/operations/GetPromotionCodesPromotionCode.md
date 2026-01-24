# GET /v1/promotion_codes/{promotion_code}

**Resource:** [promotion_codes](../resources/promotion-codes.md)
**Retrieve a promotion code**
**Operation ID:** `GetPromotionCodesPromotionCode`

<p>Retrieves the promotion code with the given ID. In order to retrieve a promotion code by the customer-facing <code>code</code> use <a href="/docs/api/promotion_codes/list">list</a> with the desired <code>code</code>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `promotion_code` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[promotion_code](../schemas/promotion/promotion-code.md)

