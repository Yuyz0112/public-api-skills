# Issue worklog properties

This resource represents [issue worklog](#api-group-Issue-worklogs) properties, which provides for storing custom data against an issue worklog. Use it to get, create, and delete issue worklog properties as well as obtain the keys of all properties on a issue worklog. Issue worklog properties are a type of [entity property](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issue/{issueIdOrKey}/worklog/{worklogId}/properties` | Get worklog property keys | [View](../operations/getWorklogPropertyKeys.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/worklog/{worklogId}/properties/{propertyKey}` | Get worklog property | [View](../operations/getWorklogProperty.md) |
| PUT | `/rest/api/3/issue/{issueIdOrKey}/worklog/{worklogId}/properties/{propertyKey}` | Set worklog property | [View](../operations/setWorklogProperty.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}/worklog/{worklogId}/properties/{propertyKey}` | Delete worklog property | [View](../operations/deleteWorklogProperty.md) |
