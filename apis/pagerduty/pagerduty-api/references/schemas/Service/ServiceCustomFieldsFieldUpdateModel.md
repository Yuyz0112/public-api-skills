# ServiceCustomFieldsFieldUpdateModel

Details of the custom field to be updated.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | [description](description.md) | No |  |
| `display_name` | [display_name](display-name.md) | No |  |
| `enabled` | [enabled](enabled.md) | No |  |
| `field_options` | any[] | No | List of field options to update, insert or delete. This field supports several behaviors:
  - Empty array: Deletes all field options
  - Omitting the `field_options` array entirely: Preserves all existing options
  - Not listing an existing option: Deletes that option (unless it's the current default value)
 |

