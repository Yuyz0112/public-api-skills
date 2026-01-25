# GET /business_services/priority_thresholds

**Resource:** [Business Services](../resources/Business-Services.md)
**Get the global priority threshold for a Business Service to be considered impacted by an Incident**
**Operation ID:** `getBusinessServicePriorityThresholds`

Retrieves the priority threshold information for an account.  Currently, there is a `global_threshold` that can be set for the account.  Incidents that have a priority meeting or exceeding this threshold will be considered impacting on any Business Service that depends on the Service to which the Incident belongs.
Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |
| 429 | (reference) |

