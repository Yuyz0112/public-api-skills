# workers_tail_consumers_script

A reference to a script that will consume logs from the attached Worker.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environment` | string | No | Optional environment if the Worker utilizes one. |
| `namespace` | string | No | Optional dispatch namespace the script belongs to. |
| `service` | string | Yes | Name of Worker that is to be the consumer. |

