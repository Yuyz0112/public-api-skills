# GET /v1/coupons/{coupon}

**Resource:** [coupons](../resources/coupons.md)
**Retrieve a coupon**
**Operation ID:** `GetCouponsCoupon`

<p>Retrieves the coupon with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `coupon` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[coupon](../schemas/coupon/coupon.md)

