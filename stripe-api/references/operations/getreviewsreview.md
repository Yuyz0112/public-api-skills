# GET /v1/reviews/{review}

**Resource:** [reviews](../resources/reviews.md)
**Retrieve a review**
**Operation ID:** `GetReviewsReview`

<p>Retrieves a <code>Review</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

