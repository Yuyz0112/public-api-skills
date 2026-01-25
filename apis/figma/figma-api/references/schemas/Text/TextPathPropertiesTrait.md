# TextPathPropertiesTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `characters` | string | Yes | The raw characters in the text path node. |
| `style` | [TextPathTypeStyle](TextPathTypeStyle.md) | Yes |  |
| `characterStyleOverrides` | number[] | Yes | The array corresponds to characters in the text box, where each element references the 'styleOverrideTable' to apply specific styles to each character. The array's length can be less than or equal to the number of characters due to the removal of trailing zeros. Elements with a value of 0 indicate characters that use the default type style. If the array is shorter than the total number of characters, the characters beyond the array's length also use the default style. |
| `layoutVersion` | number | No | Internal property, preserved for backward compatibility. Avoid using this value. |
| `styleOverrideTable` | object | Yes | Map from ID to TextPathTypeStyle for looking up style overrides. |

