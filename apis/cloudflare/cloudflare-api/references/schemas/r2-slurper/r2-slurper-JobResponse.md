# r2-slurper_JobResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `createdAt` | string | No |  |
| `finishedAt` | string | No |  |
| `id` | string | No |  |
| `overwrite` | boolean | No |  |
| `source` | any | No |  |
| `status` | [r2-slurper_JobStatus](r2-slurper-JobStatus.md) | No |  |
| `target` | object | No |  |

## Nested Fields

### `target`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | No |  |
| `jurisdiction` | [r2-slurper_Jurisdiction](r2-slurper-Jurisdiction.md) | No |  |
| `vendor` | enum: r2 | No |  |

