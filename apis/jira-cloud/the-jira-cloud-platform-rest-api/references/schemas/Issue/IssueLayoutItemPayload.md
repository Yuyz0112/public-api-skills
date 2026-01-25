# IssueLayoutItemPayload

Defines the payload to configure the issue layout item for a project.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `itemKey` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `properties` | object | No | Additional properties for this item. This field is only used when the type is FIELD. |
| `sectionType` | enum: content, primaryContext, secondaryContext | No | The item section type |
| `type` | enum: FIELD | No | The item type. Currently only support FIELD |

