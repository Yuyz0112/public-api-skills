# SectionTaskInsertRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `task` | string | Yes | The task to add to this section. |
| `insert_before` | string | No | An existing task within this section before which the added task should be inserted. Cannot be provided together with insert_after. |
| `insert_after` | string | No | An existing task within this section after which the added task should be inserted. Cannot be provided together with insert_before. |

