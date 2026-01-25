# DELETE /v1/coupons/{coupon}

**Resource:** [coupons](../resources/coupons.md)
**Delete a coupon**
**Operation ID:** `DeleteCouponsCoupon`

<p>You can delete coupons via the <a href="https://dashboard.stripe.com/coupons">coupon management</a> page of the Stripe dashboard. However, deleting a coupon does not affect any customers who have already applied the coupon; it means that new customers can’t redeem the coupon. You can also delete coupons via the API.</p>

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

[deleted_coupon](../schemas/deleted/deleted-coupon.md)

