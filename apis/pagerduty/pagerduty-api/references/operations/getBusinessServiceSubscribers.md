# GET /business_services/{id}/subscribers

**Resource:** [Business Services](../resources/Business-Services.md)
**List Business Service Subscribers**
**Operation ID:** `getBusinessServiceSubscribers`

Retrieve a list of Notification Subscribers on the Business Service.

<!-- theme: warning -->
> Users must be added through `POST /business_services/{id}/subscribers` to be returned from this endpoint.
Scoped OAuth requires: `subscribers.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |
| 429 | (reference) |

