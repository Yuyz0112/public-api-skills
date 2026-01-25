# copilot-usage-metrics-day

Copilot usage metrics for a given day.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date) | Yes | The date for which the usage metrics are aggregated, in `YYYY-MM-DD` format. |
| `total_active_users` | integer | No | The total number of Copilot users with activity belonging to any Copilot feature, globally, for the given day. Includes passive activity such as receiving a code suggestion, as well as engagement activity such as accepting a code suggestion or prompting chat. Does not include authentication events. Is not limited to the individual features detailed on the endpoint. |
| `total_engaged_users` | integer | No | The total number of Copilot users who engaged with any Copilot feature, for the given day. Examples include but are not limited to accepting a code suggestion, prompting Copilot chat, or triggering a PR Summary. Does not include authentication events. Is not limited to the individual features detailed on the endpoint. |
| `copilot_ide_code_completions` | [copilot-ide-code-completions](copilot-ide-code-completions.md) | No |  |
| `copilot_ide_chat` | [copilot-ide-chat](copilot-ide-chat.md) | No |  |
| `copilot_dotcom_chat` | [copilot-dotcom-chat](copilot-dotcom-chat.md) | No |  |
| `copilot_dotcom_pull_requests` | [copilot-dotcom-pull-requests](copilot-dotcom-pull-requests.md) | No |  |

