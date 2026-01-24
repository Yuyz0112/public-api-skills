# POST /v1/promotion_codes/{promotion_code}

**Resource:** [promotion_codes](../resources/promotion-codes.md)
**Update a promotion code**
**Operation ID:** `PostPromotionCodesPromotionCode`

<p>Updates the specified promotion code by setting the values of the parameters passed. Most fields are, by design, not editable.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

