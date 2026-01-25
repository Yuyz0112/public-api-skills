# User properties

This resource represents [user](#api-group-Users) properties and provides for storing custom data against a user. Use it to get, create, and delete user properties as well as get a list of property keys for a user. This resourse is designed for integrations and apps to store per-user data and settings. This enables data used to customized the user experience to be kept in the Jira Cloud instance's database. User properties are a type of [entity property](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/).

This resource does not access the [user properties](https://confluence.atlassian.com/x/8YxjL) created and maintained in Jira.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/user/properties` | Get user property keys | [View](../operations/getUserPropertyKeys.md) |
| GET | `/rest/api/3/user/properties/{propertyKey}` | Get user property | [View](../operations/getUserProperty.md) |
| PUT | `/rest/api/3/user/properties/{propertyKey}` | Set user property | [View](../operations/setUserProperty.md) |
| DELETE | `/rest/api/3/user/properties/{propertyKey}` | Delete user property | [View](../operations/deleteUserProperty.md) |
