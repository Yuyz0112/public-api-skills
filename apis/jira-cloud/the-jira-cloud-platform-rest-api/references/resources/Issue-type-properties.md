# Issue type properties

This resource represents [issue type](#api-group-Issue-types) properties, which provides for storing custom data against an issue type. Use it to get, create, and delete issue type properties as well as obtain the keys of all properties on a issues type. Issue type properties are a type of [entity property](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issuetype/{issueTypeId}/properties` | Get issue type property keys | [View](../operations/getIssueTypePropertyKeys.md) |
| GET | `/rest/api/3/issuetype/{issueTypeId}/properties/{propertyKey}` | Get issue type property | [View](../operations/getIssueTypeProperty.md) |
| PUT | `/rest/api/3/issuetype/{issueTypeId}/properties/{propertyKey}` | Set issue type property | [View](../operations/setIssueTypeProperty.md) |
| DELETE | `/rest/api/3/issuetype/{issueTypeId}/properties/{propertyKey}` | Delete issue type property | [View](../operations/deleteIssueTypeProperty.md) |
