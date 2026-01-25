# DevStatusTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `devStatus` | object | No | Represents whether or not a node has a particular handoff (or dev) status applied to it. |

## Nested Fields

### `devStatus`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: NONE, READY_FOR_DEV, COMPLETED | Yes |  |
| `description` | string | No | An optional field where the designer can add more information about the design and what has changed. |

