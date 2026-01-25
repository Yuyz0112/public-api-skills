# Field schemes

This resource represents field schemes which are replacing field configuration schemes to control field associations. They are currently in beta and only available to customers who have opted-in to the beta program. For more information see [RFC-103: Jira Field Configuration Overhaul: Admin Experience and API Changes](https://community.developer.atlassian.com/t/rfc-103-jira-field-configuration-overhaul-admin-experience-and-api-changes/94205)

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/config/fieldschemes` | Get field schemes | [View](../operations/getFieldAssociationSchemes.md) |
| POST | `/rest/api/3/config/fieldschemes` | Create field scheme | [View](../operations/createFieldAssociationScheme.md) |
| PUT | `/rest/api/3/config/fieldschemes/fields` | Update fields associated with field schemes | [View](../operations/updateFieldsAssociatedWithSchemes.md) |
| DELETE | `/rest/api/3/config/fieldschemes/fields` | Remove fields associated with field schemes | [View](../operations/removeFieldsAssociatedWithSchemes.md) |
| PUT | `/rest/api/3/config/fieldschemes/fields/parameters` | Update field parameters | [View](../operations/updateFieldAssociationSchemeItemParameters.md) |
| DELETE | `/rest/api/3/config/fieldschemes/fields/parameters` | Remove field parameters | [View](../operations/removeFieldAssociationSchemeItemParameters.md) |
| GET | `/rest/api/3/config/fieldschemes/projects` | Get projects with field schemes | [View](../operations/getProjectsWithFieldSchemes.md) |
| PUT | `/rest/api/3/config/fieldschemes/projects` | Associate projects to field schemes | [View](../operations/associateProjectsToFieldAssociationSchemes.md) |
| GET | `/rest/api/3/config/fieldschemes/{id}` | Get field scheme | [View](../operations/getFieldAssociationSchemeById.md) |
| PUT | `/rest/api/3/config/fieldschemes/{id}` | Update field scheme | [View](../operations/updateFieldAssociationScheme.md) |
| DELETE | `/rest/api/3/config/fieldschemes/{id}` | Delete a field scheme | [View](../operations/deleteFieldAssociationScheme.md) |
| GET | `/rest/api/3/config/fieldschemes/{id}/fields` | Search field scheme fields | [View](../operations/searchFieldAssociationSchemeFields.md) |
| GET | `/rest/api/3/config/fieldschemes/{id}/fields/{fieldId}/parameters` | Get field parameters | [View](../operations/getFieldAssociationSchemeItemParameters.md) |
| GET | `/rest/api/3/config/fieldschemes/{id}/projects` | Search field scheme projects | [View](../operations/searchFieldAssociationSchemeProjects.md) |
