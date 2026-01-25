# ResourceExportRequestParameter

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource_type` | string | No | The type of the resource to be exported. This can be a task, team, or message. |
| `filters` | [ResourceExportFilters](ResourceExportFilters.md) | No |  |
| `fields` | string[] | No | An array of fields to include for the resource type. If not provided, all non-optional fields for the resource type will be included. This conforms to the fields optional parameter available for all Asana endpoints which is documented [here](https://developers.asana.com/docs/inputoutput-options) |

