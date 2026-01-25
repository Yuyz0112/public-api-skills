# actions-hosted-runner-machine-spec

Provides details of a particular machine spec.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID used for the `size` parameter when creating a new runner. |
| `cpu_cores` | integer | Yes | The number of cores. |
| `memory_gb` | integer | Yes | The available RAM for the machine spec. |
| `storage_gb` | integer | Yes | The available SSD storage for the machine spec. |

