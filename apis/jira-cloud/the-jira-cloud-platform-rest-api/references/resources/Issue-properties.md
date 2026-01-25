# Issue properties

This resource represents [issue](#api-group-Issues) properties, which provides for storing custom data against an issue. Use it to get, set, and delete issue properties as well as obtain details of all properties on an issue. Operations to bulk update and delete issue properties are also provided. Issue properties are a type of [entity property](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rest/api/3/issue/properties` | Bulk set issues properties by list | [View](../operations/bulkSetIssuesPropertiesList.md) |
| POST | `/rest/api/3/issue/properties/multi` | Bulk set issue properties by issue | [View](../operations/bulkSetIssuePropertiesByIssue.md) |
| PUT | `/rest/api/3/issue/properties/{propertyKey}` | Bulk set issue property | [View](../operations/bulkSetIssueProperty.md) |
| DELETE | `/rest/api/3/issue/properties/{propertyKey}` | Bulk delete issue property | [View](../operations/bulkDeleteIssueProperty.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/properties` | Get issue property keys | [View](../operations/getIssuePropertyKeys.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/properties/{propertyKey}` | Get issue property | [View](../operations/getIssueProperty.md) |
| PUT | `/rest/api/3/issue/{issueIdOrKey}/properties/{propertyKey}` | Set issue property | [View](../operations/setIssueProperty.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}/properties/{propertyKey}` | Delete issue property | [View](../operations/deleteIssueProperty.md) |
