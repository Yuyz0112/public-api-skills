# POST /business_services/{id}/unsubscribe

**Resource:** [Business Services](../resources/Business-Services.md)
**Remove Business Service Subscribers**
**Operation ID:** `removeBusinessServiceNotificationSubscriber`

Unsubscribes the matching Subscribers from a Business Service.

Scoped OAuth requires: `subscribers.write`


## Request Body

The entities to unsubscribe.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

