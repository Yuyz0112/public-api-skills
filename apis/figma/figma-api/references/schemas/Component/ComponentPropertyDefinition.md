# ComponentPropertyDefinition

A property of a component.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | [ComponentPropertyType](ComponentPropertyType.md) | Yes |  |
| `defaultValue` | any | Yes | Initial value of this property for instances. |
| `variantOptions` | string[] | No | All possible values for this property. Only exists on VARIANT properties. |
| `preferredValues` | InstanceSwapPreferredValue[] | No | Preferred values for this property. Only applicable if type is `INSTANCE_SWAP`. |

