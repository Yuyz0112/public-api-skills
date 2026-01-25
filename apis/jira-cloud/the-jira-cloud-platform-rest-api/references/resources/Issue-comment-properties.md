# Issue comment properties

This resource represents [issue comment](#api-group-Issue-comments) properties, which provides for storing custom data against an issue comment. Use is to get, set, and delete issue comment properties as well as obtain the keys of all properties on a comment. Comment properties are a type of [entity property](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/comment/{commentId}/properties` | Get comment property keys | [View](../operations/getCommentPropertyKeys.md) |
| GET | `/rest/api/3/comment/{commentId}/properties/{propertyKey}` | Get comment property | [View](../operations/getCommentProperty.md) |
| PUT | `/rest/api/3/comment/{commentId}/properties/{propertyKey}` | Set comment property | [View](../operations/setCommentProperty.md) |
| DELETE | `/rest/api/3/comment/{commentId}/properties/{propertyKey}` | Delete comment property | [View](../operations/deleteCommentProperty.md) |
