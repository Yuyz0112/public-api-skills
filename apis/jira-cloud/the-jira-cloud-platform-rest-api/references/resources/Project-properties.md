# Project properties

This resource represents [project](#api-group-Projects) properties, which provides for storing custom data against a project. Use it to get, create, and delete project properties as well as get a list of property keys for a project. Project properties are a type of [entity property](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/project/{projectIdOrKey}/properties` | Get project property keys | [View](../operations/getProjectPropertyKeys.md) |
| GET | `/rest/api/3/project/{projectIdOrKey}/properties/{propertyKey}` | Get project property | [View](../operations/getProjectProperty.md) |
| PUT | `/rest/api/3/project/{projectIdOrKey}/properties/{propertyKey}` | Set project property | [View](../operations/setProjectProperty.md) |
| DELETE | `/rest/api/3/project/{projectIdOrKey}/properties/{propertyKey}` | Delete project property | [View](../operations/deleteProjectProperty.md) |
