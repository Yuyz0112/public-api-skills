# BaseTypeStyle

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fontFamily` | string | No | Font family of text (standard name). |
| `fontPostScriptName` | string,null | No | PostScript font name. |
| `fontStyle` | string | No | Describes visual weight or emphasis, such as Bold or Italic. |
| `italic` | boolean | No | Whether or not text is italicized. |
| `fontWeight` | number | No | Numeric font weight. |
| `fontSize` | number | No | Font size in px. |
| `textCase` | enum: ORIGINAL, UPPER, LOWER... | No | Text casing applied to the node, default is the original casing. |
| `textAlignHorizontal` | enum: LEFT, RIGHT, CENTER... | No | Horizontal text alignment as string enum. |
| `textAlignVertical` | enum: TOP, CENTER, BOTTOM | No | Vertical text alignment as string enum. |
| `letterSpacing` | number | No | Space between characters in px. |
| `fills` | Paint[] | No | An array of fill paints applied to the characters. |
| `hyperlink` | [Hyperlink](Hyperlink.md) | No |  |
| `opentypeFlags` | object | No | A map of OpenType feature flags to 1 or 0, 1 if it is enabled and 0 if it is disabled. Note that some flags aren't reflected here. For example, SMCP (small caps) is still represented by the `textCase` field. |
| `semanticWeight` | enum: BOLD, NORMAL | No | Indicates how the font weight was overridden when there is a text style override. |
| `semanticItalic` | enum: ITALIC, NORMAL | No | Indicates how the font style was overridden when there is a text style override. |

