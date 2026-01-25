# ScreenSchemeDetails

Details of a screen scheme.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the screen scheme. The maximum length is 255 characters. |
| `name` | string | Yes | The name of the screen scheme. The name must be unique. The maximum length is 255 characters. |
| `screens` | any | Yes | The IDs of the screens for the screen types of the screen scheme. Only screens used in classic projects are accepted. |

