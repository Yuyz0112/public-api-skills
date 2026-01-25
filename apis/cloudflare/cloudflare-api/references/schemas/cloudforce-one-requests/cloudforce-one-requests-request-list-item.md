# cloudforce-one-requests_request-list-item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `completed` | any | No | Request completion time. |
| `created` | any | Yes | Request creation time. |
| `id` | [cloudforce-one-requests_uuid](cloudforce-one-requests-uuid.md) | Yes |  |
| `message_tokens` | integer | No | Tokens for the request messages. |
| `priority` | [cloudforce-one-requests_priority](cloudforce-one-requests-priority.md) | Yes |  |
| `readable_id` | [cloudforce-one-requests_request-readable-id](cloudforce-one-requests-request-readable-id.md) | No |  |
| `request` | [cloudforce-one-requests_request-type](cloudforce-one-requests-request-type.md) | Yes |  |
| `status` | [cloudforce-one-requests_request-status](cloudforce-one-requests-request-status.md) | No |  |
| `summary` | [cloudforce-one-requests_request-summary](cloudforce-one-requests-request-summary.md) | Yes |  |
| `tlp` | [cloudforce-one-requests_tlp](cloudforce-one-requests-tlp.md) | Yes |  |
| `tokens` | integer | No | Tokens for the request. |
| `updated` | any | Yes | Request last updated time. |

