# AutomationActionsAbstractActionPutBody

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `description` | string | No |  |
| `action_classification` | [AutomationActionsActionClassificationEnum](AutomationActionsActionClassificationEnum.md) | No |  |
| `action_type` | [schema](schema.md) | No |  |
| `runner` | string | No |  |
| `only_invocable_on_unresolved_incidents` | boolean | No | If true, the action can only be invoked against an unresolved incident. |
| `allow_invocation_manually` | boolean | No | If true, the action can only be invoked manually by a user. |
| `allow_invocation_from_event_orchestration` | boolean | No | If true, the action can only be invoked automatically by an Event Orchestration. |
| `map_to_all_services` | boolean | No | If true, the action will be associated with every service. |

