# NotificationEvent

Details about a notification event.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the event. |
| `id` | integer (int64) | No | The ID of the event. The event can be a [Jira system event](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-eventsEvents) or a [custom event](https://confluence.atlassian.com/x/AIlKLg). |
| `name` | string | No | The name of the event. |
| `templateEvent` | any | No | The template of the event. Only custom events configured by Jira administrators have template. |

