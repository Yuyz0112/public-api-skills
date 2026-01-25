# repository-ruleset-conditions-repository-property-spec

Parameters for a targeting a repository property

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the repository property to target |
| `property_values` | string[] | Yes | The values to match for the repository property |
| `source` | enum: custom, system | No | The source of the repository property. Defaults to 'custom' if not specified. |

