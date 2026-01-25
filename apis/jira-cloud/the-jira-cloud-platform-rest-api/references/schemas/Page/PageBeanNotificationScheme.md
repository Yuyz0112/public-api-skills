# PageBeanNotificationScheme

A page of items.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isLast` | boolean | No | Whether this is the last page. |
| `maxResults` | integer (int32) | No | The maximum number of items that could be returned. |
| `nextPage` | string (uri) | No | If there is another page of results, the URL of the next page. |
| `self` | string (uri) | No | The URL of the page. |
| `startAt` | integer (int64) | No | The index of the first item returned. |
| `total` | integer (int64) | No | The number of items returned. |
| `values` | NotificationScheme[] | No | The list of items. |

