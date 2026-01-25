# email-security_PhishGuardReport

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content` | string | Yes |  |
| `disposition` | [email-security_DispositionLabel](email-security-DispositionLabel.md) | Yes |  |
| `fields` | object | Yes |  |
| `id` | integer (int32) | Yes |  |
| `priority` | string | Yes |  |
| `tags` | email-security_PhishGuardReportTag[] | No |  |
| `title` | string | Yes |  |
| `ts` | string (date-time) | Yes |  |

## Nested Fields

### `fields`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `postfix_id` | string | No |  |
| `to` | string[] | Yes |  |
| `ts` | string (date-time) | Yes |  |

