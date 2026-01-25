# DELETE /business_services/priority_thresholds

**Resource:** [Business Services](../resources/Business-Services.md)
**Deletes the account-level priority threshold for Business Service impact**
**Operation ID:** `deleteBusinessServicePriorityThresholds`

Clears the Priority Threshold for the account.  If the priority threshold is cleared, any Incident with a Priority set will be able to impact Business Services.
Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Priority Threshold for the account was successfully cleared. |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

