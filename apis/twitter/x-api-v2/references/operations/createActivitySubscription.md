# POST /2/activity/subscriptions

**Resource:** [Activity](../resources/Activity.md)
**Create X activity subscription**
**Operation ID:** `createActivitySubscription`

Creates a subscription for an X activity event

## Request Body

**Content Types:** `application/json`

**Schema:** [ActivitySubscriptionCreateRequest](../schemas/Activity/ActivitySubscriptionCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ActivitySubscriptionCreateResponse](../schemas/Activity/ActivitySubscriptionCreateResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: dm.read, tweet.read
- **UserToken**
