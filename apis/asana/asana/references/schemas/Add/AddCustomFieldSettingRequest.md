# AddCustomFieldSettingRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `custom_field` | any | Yes |  |
| `is_important` | boolean | No | Whether this field should be considered important to this container (for instance, to display in the list view of items in the container). |
| `insert_before` | string | No | A gid of a Custom Field Setting on this container, before which the new Custom Field Setting will be added.  `insert_before` and `insert_after` parameters cannot both be specified. |
| `insert_after` | string | No | A gid of a Custom Field Setting on this container, after which the new Custom Field Setting will be added.  `insert_before` and `insert_after` parameters cannot both be specified. |

