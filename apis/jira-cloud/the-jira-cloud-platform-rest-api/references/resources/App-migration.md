# App migration

This resource supports [app migrations](https://developer.atlassian.com/platform/app-migration/). Use it to:
- [to request migrated workflow rules details](https://developer.atlassian.com/platform/app-migration/tutorials/migration-app-workflow-rules/).
- [perform bulk updates of entity properties](https://developer.atlassian.com/platform/app-migration/tutorials/entity-properties-bulk-api/).
- [perform bulk updates of issue custom field values](https://developer.atlassian.com/platform/app-migration/tutorials/migrating-app-custom-fields/).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| PUT | `/rest/atlassian-connect/1/migration/field` | Bulk update custom field value | [View](../operations/AppIssueFieldValueUpdateResource-updateIssueFields-put.md) |
| PUT | `/rest/atlassian-connect/1/migration/properties/{entityType}` | Bulk update entity properties | [View](../operations/MigrationResource-updateEntityPropertiesValue-put.md) |
| POST | `/rest/atlassian-connect/1/migration/workflow/rule/search` | Get workflow transition rule configurations | [View](../operations/MigrationResource-workflowRuleSearch-post.md) |
