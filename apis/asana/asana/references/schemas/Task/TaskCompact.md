# TaskCompact

The *task* is the basic object around which many operations in Asana are centered.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `name` | string | No | The name of the task. |
| `resource_subtype` | enum: default_task, milestone, approval | No | The subtype of this resource. Different subtypes retain many of the same fields and behavior, but may render differently in Asana or represent resources with different semantic meaning.
The resource_subtype `milestone` represent a single moment in time. This means tasks with this subtype cannot have a start_date. |
| `created_by` | object | No | [Opt In](/docs/inputoutput-options). A *user* object represents an account in Asana that can be given access to various workspaces, projects, and tasks. |

## Nested Fields

### `created_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource. |
| `resource_type` | string | No | The type of resource. |

