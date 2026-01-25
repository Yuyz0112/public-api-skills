# POST /business_services/{id}/subscribers

**Resource:** [Business Services](../resources/Business-Services.md)
**Create Business Service Subscribers**
**Operation ID:** `createBusinessServiceNotificationSubscribers`

Subscribe the given entities to the given Business Service.

Scoped OAuth requires: `subscribers.write`


## Request Body

The entities to subscribe.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

