# custom-property-set-payload

Custom property set payload

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value_type` | enum: string, single_select, multi_select... | Yes | The type of the value for the property |
| `required` | boolean | No | Whether the property is required. |
| `default_value` | any | No | Default value of the property |
| `description` | string | No | Short description of the property |
| `allowed_values` | string[] | No | An ordered list of the allowed values of the property.
The property can have up to 200 allowed values. |
| `values_editable_by` | enum: org_actors, org_and_repo_actors | No | Who can edit the values of the property |

