# StatusPageService

A Service represents a PagerDuty service that is linked to a Status Page.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | An unique identifier within Status Page scope that defines a Service entry. |
| `self` | string | No | The API resource URL of the Service. |
| `name` | string | No | The name of the Service. |
| `status_page` | object | No | Status Page |
| `business_service` | any | No | Business Service |
| `type` | string | No | A string that determines the schema of the object. |

## Nested Fields

### `status_page`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

