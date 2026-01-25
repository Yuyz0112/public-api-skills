# GET /user/marketplace_purchases/stubbed

**Resource:** [apps](../resources/apps.md)
**List subscriptions for the authenticated user (stubbed)**
**Operation ID:** `apps/list-subscriptions-for-authenticated-user-stubbed`

Lists the active subscriptions for the authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |

**Success Response Schema:**

Array of [user-marketplace-purchase](../schemas/user-marketplace-purchase/user-marketplace-purchase.md)

