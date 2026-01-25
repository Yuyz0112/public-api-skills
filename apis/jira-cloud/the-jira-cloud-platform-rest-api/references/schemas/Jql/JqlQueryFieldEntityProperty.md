# JqlQueryFieldEntityProperty

Details of an entity property.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `entity` | string | Yes | The object on which the property is set. |
| `key` | string | Yes | The key of the property. |
| `path` | string | Yes | The path in the property value to query. |
| `type` | enum: number, string, text... | No | The type of the property value extraction. Not available if the extraction for the property is not registered on the instance with the [Entity property](https://developer.atlassian.com/cloud/jira/platform/modules/entity-property/) module. |

