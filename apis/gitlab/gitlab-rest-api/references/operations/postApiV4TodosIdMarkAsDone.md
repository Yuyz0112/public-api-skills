# POST /api/v4/todos/{id}/mark_as_done

**Resource:** [To-dos](../resources/To-dos.md)
**Mark a to-do item as done**
**Operation ID:** `postApiV4TodosIdMarkAsDone`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of to-do item |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesTodo](../schemas/APIEntitiesTodo/APIEntitiesTodo.md)

