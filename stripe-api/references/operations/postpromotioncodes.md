# POST /v1/promotion_codes

**Resource:** [promotion_codes](../resources/promotion-codes.md)
**Create a promotion code**
**Operation ID:** `PostPromotionCodes`

<p>A promotion code points to an underlying promotion. You can optionally restrict the code to a specific customer, redemption limit, and expiration date.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[promotion_code](../schemas/promotion/promotion-code.md)

