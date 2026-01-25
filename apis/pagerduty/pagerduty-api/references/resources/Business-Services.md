# Business Services

Business services model capabilities that span multiple technical services and that may be owned by several different teams.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/business_services` | List Business Services | [View](../operations/listBusinessServices.md) |
| POST | `/business_services` | Create a Business Service | [View](../operations/createBusinessService.md) |
| GET | `/business_services/{id}` | Get a Business Service | [View](../operations/getBusinessService.md) |
| PUT | `/business_services/{id}` | Update a Business Service | [View](../operations/updateBusinessService.md) |
| DELETE | `/business_services/{id}` | Delete a Business Service | [View](../operations/deleteBusinessService.md) |
| POST | `/business_services/{id}/account_subscription` | Create Business Service Account Subscription | [View](../operations/createBusinessServiceAccountSubscription.md) |
| DELETE | `/business_services/{id}/account_subscription` | Delete Business Service Account Subscription | [View](../operations/removeBusinessServiceAccountSubscription.md) |
| GET | `/business_services/{id}/subscribers` | List Business Service Subscribers | [View](../operations/getBusinessServiceSubscribers.md) |
| POST | `/business_services/{id}/subscribers` | Create Business Service Subscribers | [View](../operations/createBusinessServiceNotificationSubscribers.md) |
| GET | `/business_services/{id}/supporting_services/impacts` | List the supporting Business Services for the given Business Service Id, sorted by impacted status. | [View](../operations/getBusinessServiceSupportingServiceImpacts.md) |
| POST | `/business_services/{id}/unsubscribe` | Remove Business Service Subscribers | [View](../operations/removeBusinessServiceNotificationSubscriber.md) |
| GET | `/business_services/impactors` | List Impactors affecting Business Services | [View](../operations/getBusinessServiceTopLevelImpactors.md) |
| GET | `/business_services/impacts` | List Business Services sorted by impacted status | [View](../operations/getBusinessServiceImpacts.md) |
| GET | `/business_services/priority_thresholds` | Get the global priority threshold for a Business Service to be considered impacted by an Incident | [View](../operations/getBusinessServicePriorityThresholds.md) |
| PUT | `/business_services/priority_thresholds` | Set the Account-level priority threshold for Business Service impact. | [View](../operations/putBusinessServicePriorityThresholds.md) |
| DELETE | `/business_services/priority_thresholds` | Deletes the account-level priority threshold for Business Service impact | [View](../operations/deleteBusinessServicePriorityThresholds.md) |
