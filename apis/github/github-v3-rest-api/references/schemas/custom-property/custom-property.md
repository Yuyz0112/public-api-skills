# custom-property

Custom property defined on an organization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `property_name` | string | Yes | The name of the property |
| `url` | string (uri) | No | The URL that can be used to fetch, update, or delete info about this property via the API. |
| `source_type` | enum: organization, enterprise | No | The source type of the property |
| `value_type` | enum: string, single_select, multi_select... | Yes | The type of the value for the property |
| `required` | boolean | No | Whether the property is required. |
| `default_value` | any | No | Default value of the property |
| `description` | string | No | Short description of the property |
| `allowed_values` | string[] | No | An ordered list of the allowed values of the property.
The property can have up to 200 allowed values. |
| `values_editable_by` | enum: org_actors, org_and_repo_actors | No | Who can edit the values of the property |

