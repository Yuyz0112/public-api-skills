# GET /user/marketplace_purchases

**Resource:** [apps](../resources/apps.md)
**List subscriptions for the authenticated user**
**Operation ID:** `apps/list-subscriptions-for-authenticated-user`

Lists the active subscriptions for the authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [user-marketplace-purchase](../schemas/user-marketplace-purchase/user-marketplace-purchase.md)

