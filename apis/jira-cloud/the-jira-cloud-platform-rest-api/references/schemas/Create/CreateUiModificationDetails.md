# CreateUiModificationDetails

The details of a UI modification.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `contexts` | UiModificationContextDetails[] | No | List of contexts of the UI modification. The maximum number of contexts is 1000. |
| `data` | string | No | The data of the UI modification. The maximum size of the data is 50000 characters. |
| `description` | string | No | The description of the UI modification. The maximum length is 255 characters. |
| `name` | string | Yes | The name of the UI modification. The maximum length is 255 characters. |

