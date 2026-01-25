# TimeTrackingProvider

Details about the time tracking provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes | The key for the time tracking provider. For example, *JIRA*. |
| `name` | string | No | The name of the time tracking provider. For example, *JIRA provided time tracking*. |
| `url` | string | No | The URL of the configuration page for the time tracking provider app. For example, */example/config/url*. This property is only returned if the `adminPageKey` property is set in the module descriptor of the time tracking provider app. |

