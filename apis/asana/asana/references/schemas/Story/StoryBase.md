# StoryBase

A story represents an activity associated with an object in the Asana system.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `created_at` | string (date-time) | No | The time at which this resource was created. |
| `resource_subtype` | string | No | The subtype of this resource. Different subtypes retain many of the same fields and behavior, but may render differently in Asana or represent resources with different semantic meaning. |
| `text` | string | No | The plain text of the comment to add. Cannot be used with html_text. |
| `html_text` | string | No | [Opt In](/docs/inputoutput-options). HTML formatted text for a comment. This will not include the name of the creator. |
| `is_pinned` | boolean | No | *Conditional*. Whether the story should be pinned on the resource. |
| `sticker_name` | enum: green_checkmark, people_dancing, dancing_unicorn... | No | The name of the sticker in this story. `null` if there is no sticker. |

