# Services

A Service may represent an application, component, or team you wish to open incidents against.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/services` | List services | [View](../operations/listServices.md) |
| POST | `/services` | Create a service | [View](../operations/createService.md) |
| GET | `/services/{id}` | Get a service | [View](../operations/getService.md) |
| PUT | `/services/{id}` | Update a service | [View](../operations/updateService.md) |
| DELETE | `/services/{id}` | Delete a service | [View](../operations/deleteService.md) |
| GET | `/services/{id}/audit/records` | List audit records for a service | [View](../operations/listServiceAuditRecords.md) |
| POST | `/services/{id}/integrations` | Create a new integration | [View](../operations/createServiceIntegration.md) |
| GET | `/services/{id}/integrations/{integration_id}` | View an integration | [View](../operations/getServiceIntegration.md) |
| PUT | `/services/{id}/integrations/{integration_id}` | Update an existing integration | [View](../operations/updateServiceIntegration.md) |
| GET | `/services/{id}/rules` | List Service's Event Rules | [View](../operations/listServiceEventRules.md) |
| POST | `/services/{id}/rules` | Create an Event Rule on a Service | [View](../operations/createServiceEventRule.md) |
| POST | `/services/{id}/rules/convert` | Convert a Service's Event Rules into Event Orchestration Rules | [View](../operations/convertServiceEventRulesToEventOrchestration.md) |
| GET | `/services/{id}/rules/{rule_id}` | Get an Event Rule from a Service | [View](../operations/getServiceEventRule.md) |
| PUT | `/services/{id}/rules/{rule_id}` | Update an Event Rule on a Service | [View](../operations/updateServiceEventRule.md) |
| DELETE | `/services/{id}/rules/{rule_id}` | Delete an Event Rule from a Service | [View](../operations/deleteServiceEventRule.md) |
| GET | `/services/{id}/custom_fields/values` | Get Custom Field Values | [View](../operations/getServiceCustomFieldValues.md) |
| PUT | `/services/{id}/custom_fields/values` | Update Custom Field Values | [View](../operations/updateServiceCustomFieldValues.md) |
| GET | `/services/{id}/enablements` | Get Enablements for a Service | [View](../operations/listServiceFeatureEnablements.md) |
| PUT | `/services/{id}/enablements/{feature_name}` | Update an Enablement for a Service | [View](../operations/updateServiceFeatureEnablement.md) |
