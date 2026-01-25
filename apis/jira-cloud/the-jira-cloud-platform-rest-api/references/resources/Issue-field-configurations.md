# Issue field configurations

This resource represents issue field configurations. Use it to get, set, and delete field configurations and field configuration schemes.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/fieldconfiguration` | Get all field configurations | [View](../operations/getAllFieldConfigurations.md) |
| POST | `/rest/api/3/fieldconfiguration` | Create field configuration | [View](../operations/createFieldConfiguration.md) |
| PUT | `/rest/api/3/fieldconfiguration/{id}` | Update field configuration | [View](../operations/updateFieldConfiguration.md) |
| DELETE | `/rest/api/3/fieldconfiguration/{id}` | Delete field configuration | [View](../operations/deleteFieldConfiguration.md) |
| GET | `/rest/api/3/fieldconfiguration/{id}/fields` | Get field configuration items | [View](../operations/getFieldConfigurationItems.md) |
| PUT | `/rest/api/3/fieldconfiguration/{id}/fields` | Update field configuration items | [View](../operations/updateFieldConfigurationItems.md) |
| GET | `/rest/api/3/fieldconfigurationscheme` | Get all field configuration schemes | [View](../operations/getAllFieldConfigurationSchemes.md) |
| POST | `/rest/api/3/fieldconfigurationscheme` | Create field configuration scheme | [View](../operations/createFieldConfigurationScheme.md) |
| GET | `/rest/api/3/fieldconfigurationscheme/mapping` | Get field configuration issue type items | [View](../operations/getFieldConfigurationSchemeMappings.md) |
| GET | `/rest/api/3/fieldconfigurationscheme/project` | Get field configuration schemes for projects | [View](../operations/getFieldConfigurationSchemeProjectMapping.md) |
| PUT | `/rest/api/3/fieldconfigurationscheme/project` | Assign field configuration scheme to project | [View](../operations/assignFieldConfigurationSchemeToProject.md) |
| PUT | `/rest/api/3/fieldconfigurationscheme/{id}` | Update field configuration scheme | [View](../operations/updateFieldConfigurationScheme.md) |
| DELETE | `/rest/api/3/fieldconfigurationscheme/{id}` | Delete field configuration scheme | [View](../operations/deleteFieldConfigurationScheme.md) |
| PUT | `/rest/api/3/fieldconfigurationscheme/{id}/mapping` | Assign issue types to field configurations | [View](../operations/setFieldConfigurationSchemeMapping.md) |
| POST | `/rest/api/3/fieldconfigurationscheme/{id}/mapping/delete` | Remove issue types from field configuration scheme | [View](../operations/removeIssueTypesFromGlobalFieldConfigurationScheme.md) |
