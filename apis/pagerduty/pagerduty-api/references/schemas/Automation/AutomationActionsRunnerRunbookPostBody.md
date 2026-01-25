# AutomationActionsRunnerRunbookPostBody

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `runner_type` | [AutomationActionsRunnerTypeEnum](AutomationActionsRunnerTypeEnum.md) | Yes |  |
| `name` | string | Yes |  |
| `description` | string | Yes |  |
| `runbook_base_uri` | [AutomationActionsRunbookBaseURI](AutomationActionsRunbookBaseURI.md) | Yes |  |
| `runbook_api_key` | string | Yes | The API key to connect to the Runbook server with. If omitted, the previously stored value will remain unchanged |
| `teams` | TeamReference[] | No | The list of teams associated with the Runner |

