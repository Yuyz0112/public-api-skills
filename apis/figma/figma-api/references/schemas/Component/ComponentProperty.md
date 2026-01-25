# ComponentProperty

A property of a component.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | [ComponentPropertyType](ComponentPropertyType.md) | Yes |  |
| `value` | any | Yes | Value of the property for this component instance. |
| `preferredValues` | InstanceSwapPreferredValue[] | No | Preferred values for this property. Only applicable if type is `INSTANCE_SWAP`. |
| `boundVariables` | object | No | The variables bound to a particular field on this component property |

## Nested Fields

### `boundVariables`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | [VariableAlias](VariableAlias.md) | No |  |

