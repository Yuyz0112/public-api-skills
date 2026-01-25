# TransitionPayload

The payload for creating a transition in a workflow. Can be DIRECTED, GLOBAL, SELF-LOOPED, GLOBAL LOOPED

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | RulePayload[] | No | The actions that are performed when the transition is made |
| `conditions` | [ConditionGroupPayload](ConditionGroupPayload.md) | No |  |
| `customIssueEventId` | string | No | Mechanism in Jira for triggering certain actions, like notifications, automations, etc. Unless a custom notification scheme is configure, it's better not to provide any value here |
| `description` | string | No | The description of the transition |
| `from` | FromLayoutPayload[] | No | The statuses that the transition can be made from |
| `id` | integer (int32) | No | The id of the transition |
| `name` | string | No | The name of the transition |
| `properties` | object | No | The properties of the transition |
| `to` | [ToLayoutPayload](ToLayoutPayload.md) | No |  |
| `transitionScreen` | [RulePayload](RulePayload.md) | No |  |
| `triggers` | RulePayload[] | No | The triggers that are performed when the transition is made |
| `type` | enum: global, initial, directed | No | The type of the transition |
| `validators` | RulePayload[] | No | The validators that are performed when the transition is made |

