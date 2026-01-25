# Issue custom field configuration (apps)

This resource represents configurations stored against a custom field context by a [Forge app](https://developer.atlassian.com/platform/forge/). Configurations are information used by the Forge app at runtime to determine how to handle or process the data in a custom field in a given context. Use this resource to set and read configurations.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rest/api/3/app/field/context/configuration/list` | Bulk get custom field configurations | [View](../operations/getCustomFieldsConfigurations.md) |
| GET | `/rest/api/3/app/field/{fieldIdOrKey}/context/configuration` | Get custom field configurations | [View](../operations/getCustomFieldConfiguration.md) |
| PUT | `/rest/api/3/app/field/{fieldIdOrKey}/context/configuration` | Update custom field configurations | [View](../operations/updateCustomFieldConfiguration.md) |
