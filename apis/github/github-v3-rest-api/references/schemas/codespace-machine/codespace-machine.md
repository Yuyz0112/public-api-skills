# codespace-machine

A description of the machine powering a codespace.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the machine. |
| `display_name` | string | Yes | The display name of the machine includes cores, memory, and storage. |
| `operating_system` | string | Yes | The operating system of the machine. |
| `storage_in_bytes` | integer | Yes | How much storage is available to the codespace. |
| `memory_in_bytes` | integer | Yes | How much memory is available to the codespace. |
| `cpus` | integer | Yes | How many cores are available to the codespace. |
| `prebuild_availability` | enum: none, ready, in_progress | Yes | Whether a prebuild is currently available when creating a codespace for this machine and repository. If a branch was not specified as a ref, the default branch will be assumed. Value will be "null" if prebuilds are not supported or prebuild availability could not be determined. Value will be "none" if no prebuild is available. Latest values "ready" and "in_progress" indicate the prebuild availability status. |

