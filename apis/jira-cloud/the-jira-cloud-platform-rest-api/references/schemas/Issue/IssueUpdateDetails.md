# IssueUpdateDetails

Details of an issue update request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fields` | object | No | List of issue screen fields to update, specifying the sub-field to update and its value for each field. This field provides a straightforward option when setting a sub-field. When multiple sub-fields or other operations are required, use `update`. Fields included in here cannot be included in `update`. |
| `historyMetadata` | any | No | Additional issue history details. |
| `properties` | EntityProperty[] | No | Details of issue properties to be add or update. |
| `transition` | any | No | Details of a transition. Required when performing a transition, optional when creating or editing an issue. |
| `update` | object | No | A Map containing the field field name and a list of operations to perform on the issue screen field. Note that fields included in here cannot be included in `fields`. |

