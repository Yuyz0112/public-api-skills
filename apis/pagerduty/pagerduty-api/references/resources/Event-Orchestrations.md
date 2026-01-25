# Event Orchestrations

Event Orchestrations allow you to route events to an endpoint and create collections of Event Orchestrations, which define sets of actions to take based on event content.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/event_orchestrations` | List Event Orchestrations | [View](../operations/listEventOrchestrations.md) |
| POST | `/event_orchestrations` | Create an Orchestration | [View](../operations/postOrchestration.md) |
| GET | `/event_orchestrations/{id}` | Get an Orchestration | [View](../operations/getOrchestration.md) |
| PUT | `/event_orchestrations/{id}` | Update an Orchestration | [View](../operations/updateOrchestration.md) |
| DELETE | `/event_orchestrations/{id}` | Delete an Orchestration | [View](../operations/deleteOrchestration.md) |
| GET | `/event_orchestrations/{id}/integrations` | List Integrations for an Event Orchestration | [View](../operations/listOrchestrationIntegrations.md) |
| POST | `/event_orchestrations/{id}/integrations` | Create an Integration for an Event Orchestration | [View](../operations/postOrchestrationIntegration.md) |
| GET | `/event_orchestrations/{id}/integrations/{integration_id}` | Get an Integration for an Event Orchestration | [View](../operations/getOrchestrationIntegration.md) |
| PUT | `/event_orchestrations/{id}/integrations/{integration_id}` | Update an Integration for an Event Orchestration | [View](../operations/updateOrchestrationIntegration.md) |
| DELETE | `/event_orchestrations/{id}/integrations/{integration_id}` | Delete an Integration for an Event Orchestration | [View](../operations/deleteOrchestrationIntegration.md) |
| POST | `/event_orchestrations/{id}/integrations/migration` | Migrate an Integration from one Event Orchestration to another | [View](../operations/migrateOrchestrationIntegration.md) |
| GET | `/event_orchestrations/{id}/global` | Get the Global Orchestration for an Event Orchestration | [View](../operations/getOrchPathGlobal.md) |
| PUT | `/event_orchestrations/{id}/global` | Update the Global Orchestration for an Event Orchestration | [View](../operations/updateOrchPathGlobal.md) |
| GET | `/event_orchestrations/{id}/router` | Get the Router for an Event Orchestration | [View](../operations/getOrchPathRouter.md) |
| PUT | `/event_orchestrations/{id}/router` | Update the Router for an Event Orchestration | [View](../operations/updateOrchPathRouter.md) |
| GET | `/event_orchestrations/{id}/unrouted` | Get the Unrouted Orchestration for an Event Orchestration | [View](../operations/getOrchPathUnrouted.md) |
| PUT | `/event_orchestrations/{id}/unrouted` | Update the Unrouted Orchestration for an Event Orchestration | [View](../operations/updateOrchPathUnrouted.md) |
| GET | `/event_orchestrations/services/{service_id}` | Get the Service Orchestration for a Service | [View](../operations/getOrchPathService.md) |
| PUT | `/event_orchestrations/services/{service_id}` | Update the Service Orchestration for a Service | [View](../operations/updateOrchPathService.md) |
| GET | `/event_orchestrations/services/{service_id}/active` | Get the Service Orchestration active status for a Service | [View](../operations/getOrchActiveStatus.md) |
| PUT | `/event_orchestrations/services/{service_id}/active` | Update the Service Orchestration active status for a Service | [View](../operations/updateOrchActiveStatus.md) |
| GET | `/event_orchestrations/{id}/cache_variables` | List Cache Variables for a Global Event Orchestration | [View](../operations/listCacheVarOnGlobalOrch.md) |
| POST | `/event_orchestrations/{id}/cache_variables` | Create a Cache Variable for a Global Event Orchestration | [View](../operations/createCacheVarOnGlobalOrch.md) |
| GET | `/event_orchestrations/{id}/cache_variables/{cache_variable_id}` | Get a Cache Variable for a Global Event Orchestration | [View](../operations/getCacheVarOnGlobalOrch.md) |
| PUT | `/event_orchestrations/{id}/cache_variables/{cache_variable_id}` | Update a Cache Variable for a Global Event Orchestration | [View](../operations/updateCacheVarOnGlobalOrch.md) |
| DELETE | `/event_orchestrations/{id}/cache_variables/{cache_variable_id}` | Delete a Cache Variable for a Global Event Orchestration | [View](../operations/deleteCacheVarOnGlobalOrch.md) |
| GET | `/event_orchestrations/{id}/cache_variables/{cache_variable_id}/data` | Get Data for an External Data Cache Variable on a Global Event Orchestration | [View](../operations/getExternalDataCacheVarDataOnGlobalOrch.md) |
| PUT | `/event_orchestrations/{id}/cache_variables/{cache_variable_id}/data` | Update Data for an External Data Cache Variable on a Global Event Orchestration | [View](../operations/updateExternalDataCacheVarDataOnGlobalOrch.md) |
| DELETE | `/event_orchestrations/{id}/cache_variables/{cache_variable_id}/data` | Delete Data for an External Data Cache Variable on a Global Event Orchestration | [View](../operations/deleteExternalDataCacheVarDataOnGlobalOrch.md) |
| GET | `/event_orchestrations/services/{service_id}/cache_variables` | List Cache Variables for a Service Event Orchestration | [View](../operations/listCacheVarOnServiceOrch.md) |
| POST | `/event_orchestrations/services/{service_id}/cache_variables` | Create a Cache Variable for a Service Event Orchestration | [View](../operations/createCacheVarOnServiceOrch.md) |
| GET | `/event_orchestrations/services/{service_id}/cache_variables/{cache_variable_id}` | Get a Cache Variable for a Service Event Orchestration | [View](../operations/getCacheVarOnServiceOrch.md) |
| PUT | `/event_orchestrations/services/{service_id}/cache_variables/{cache_variable_id}` | Update a Cache Variable for a Service Event Orchestration | [View](../operations/updateCacheVarOnServiceOrch.md) |
| DELETE | `/event_orchestrations/services/{service_id}/cache_variables/{cache_variable_id}` | Delete a Cache Variable for a Service Event Orchestration | [View](../operations/deleteCacheVarOnServiceOrch.md) |
| GET | `/event_orchestrations/services/{service_id}/cache_variables/{cache_variable_id}/data` | Get Data for an External Data Cache Variable on a Service Event Orchestration | [View](../operations/getExternalDataCacheVarDataOnServiceOrch.md) |
| PUT | `/event_orchestrations/services/{service_id}/cache_variables/{cache_variable_id}/data` | Update Data for an External Data Cache Variable on a Service Event Orchestration | [View](../operations/updateExternalDataCacheVarDataOnServiceOrch.md) |
| DELETE | `/event_orchestrations/services/{service_id}/cache_variables/{cache_variable_id}/data` | Delete Data for an External Data Cache Variable on a Service Event Orchestration | [View](../operations/deleteExternalDataCacheVarDataOnServiceOrch.md) |
| GET | `/event_orchestrations/{id}/enablements` | List Enablements for an Event Orchestration | [View](../operations/listEventOrchestrationFeatureEnablements.md) |
| PUT | `/event_orchestrations/{id}/enablements/{feature_name}` | Update an Enablement for an Event Orchestration | [View](../operations/updateEventOrchestrationFeatureEnablements.md) |
