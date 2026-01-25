# PUT /business_services/priority_thresholds

**Resource:** [Business Services](../resources/Business-Services.md)
**Set the Account-level priority threshold for Business Service impact.**
**Operation ID:** `putBusinessServicePriorityThresholds`

Set the Account-level priority threshold for Business Service.
Scoped OAuth requires: `services.write`


## Request Body

Set the `id` and `order` of the global Priority Threshold. These values can be obtained by calling the `/priorities` endpoint.

Once set, Incidents must be at or above the specified level in order to impact Business Services.  An exception to this rule is if the Incident has been added to the incident directly using the `PUT /incidents/{id}/business_services/{business_service_id}/impacts` endpoint.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |
| 429 | (reference) |
| 500 | Internal Server Error |

