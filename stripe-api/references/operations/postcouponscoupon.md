# POST /v1/coupons/{coupon}

**Resource:** [coupons](../resources/coupons.md)
**Update a coupon**
**Operation ID:** `PostCouponsCoupon`

<p>Updates the metadata of a coupon. Other coupon details (currency, duration, amount_off) are, by design, not editable.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `coupon` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[coupon](../schemas/coupon/coupon.md)

