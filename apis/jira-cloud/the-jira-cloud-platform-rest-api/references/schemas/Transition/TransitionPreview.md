# TransitionPreview

Details about a workflow transition in preview context.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | PreviewRuleConfiguration[] | No | The post-functions of the transition. |
| `conditions` | [PreviewConditionGroupConfiguration](PreviewConditionGroupConfiguration.md) | No |  |
| `customIssueEventId` | string | No | The custom issue event ID for the transition. |
| `description` | string | No | The description of the transition. |
| `id` | string | No | The ID of the transition. |
| `links` | TransitionLink[] | No | The statuses the transition can start from, and the mapping of ports between the statuses. |
| `name` | string | No | The name of the transition. |
| `toStatusReference` | string | No | The status the transition goes to. |
| `transitionScreen` | [PreviewRuleConfiguration](PreviewRuleConfiguration.md) | No |  |
| `triggers` | PreviewTrigger[] | No | The triggers of the transition. |
| `type` | enum: INITIAL, GLOBAL, DIRECTED | No | The transition type. |
| `validators` | PreviewRuleConfiguration[] | No | The validators of the transition. |

