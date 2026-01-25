# SectionRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The text to be displayed as the section name. This cannot be an empty string. |
| `insert_before` | string | No | An existing section within this project before which the added section should be inserted. Cannot be provided together with insert_after. |
| `insert_after` | string | No | An existing section within this project after which the added section should be inserted. Cannot be provided together with insert_before. |

