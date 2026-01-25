# PUT /event_orchestrations/services/{service_id}/cache_variables/{cache_variable_id}/data

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Update Data for an External Data Cache Variable on a Service Event Orchestration**
**Operation ID:** `updateExternalDataCacheVarDataOnServiceOrch`

Update the data for an `external_data` type Cache Variable on a Service Event Orchestration.

Use External Data type Cache Variables to store string, number, or boolean values via a dedicated API endpoint. These stored values can then be used in conditions or actions in Event Orchestration rules.

For more information see the [Knowledge Base](https://support.pagerduty.com/main/docs/event-orchestration-cache-variables)

Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |

