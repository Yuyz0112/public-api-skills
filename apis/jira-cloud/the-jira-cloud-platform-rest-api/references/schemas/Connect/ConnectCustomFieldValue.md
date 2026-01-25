# ConnectCustomFieldValue

A list of custom field details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `_type` | enum: StringIssueField, NumberIssueField, RichTextIssueField... | Yes | The type of custom field. |
| `fieldID` | integer | Yes | The custom field ID. |
| `issueID` | integer | Yes | The issue ID. |
| `number` | number | No | The value of number type custom field when `_type` is `NumberIssueField`. |
| `optionID` | string | No | The value of single select and multiselect custom field type when `_type` is `SingleSelectIssueField` or `MultiSelectIssueField`. |
| `richText` | string | No | The value of richText type custom field when `_type` is `RichTextIssueField`. |
| `string` | string | No | The value of string type custom field when `_type` is `StringIssueField`. |
| `text` | string | No | The value of of text custom field type when `_type` is `TextIssueField`. |

