# StoryCompact

A story represents an activity associated with an object in the Asana system.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `created_at` | string (date-time) | No | The time at which this resource was created. |
| `created_by` | [UserCompact](UserCompact.md) | No |  |
| `resource_subtype` | string | No | The subtype of this resource. Different subtypes retain many of the same fields and behavior, but may render differently in Asana or represent resources with different semantic meaning. |
| `text` | string | No | *Create-only*. Human-readable text for the story or comment.
This will not include the name of the creator.
*Note: This is not guaranteed to be stable for a given type of story. For example, text for a reassignment may not always say “assigned to …” as the text for a story can both be edited and change based on the language settings of the user making the request.*
Use the `resource_subtype` property to discover the action that created the story. |

