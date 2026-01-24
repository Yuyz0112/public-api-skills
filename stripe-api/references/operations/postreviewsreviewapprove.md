# POST /v1/reviews/{review}/approve

**Resource:** [reviews](../resources/reviews.md)
**Approve a review**
**Operation ID:** `PostReviewsReviewApprove`

<p>Approves a <code>Review</code> object, closing it and removing it from the list of reviews.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `review` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[review](../schemas/review/review.md)

