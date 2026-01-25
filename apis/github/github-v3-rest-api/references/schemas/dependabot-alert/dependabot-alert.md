# dependabot-alert

A Dependabot alert.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `number` | [alert-number](alert-number.md) | Yes |  |
| `state` | enum: auto_dismissed, dismissed, fixed... | Yes | The state of the Dependabot alert. |
| `dependency` | object | Yes | Details for the vulnerable dependency. |
| `security_advisory` | [dependabot-alert-security-advisory](dependabot-alert-security-advisory.md) | Yes |  |
| `security_vulnerability` | [dependabot-alert-security-vulnerability](dependabot-alert-security-vulnerability.md) | Yes |  |
| `url` | [alert-url](alert-url.md) | Yes |  |
| `html_url` | [alert-html-url](alert-html-url.md) | Yes |  |
| `created_at` | [alert-created-at](alert-created-at.md) | Yes |  |
| `updated_at` | [alert-updated-at](alert-updated-at.md) | Yes |  |
| `dismissed_at` | [alert-dismissed-at](alert-dismissed-at.md) | Yes |  |
| `dismissed_by` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `dismissed_reason` | enum: fix_started, inaccurate, no_bandwidth... | Yes | The reason that the alert was dismissed. |
| `dismissed_comment` | string | Yes | An optional comment associated with the alert's dismissal. |
| `fixed_at` | [alert-fixed-at](alert-fixed-at.md) | Yes |  |
| `auto_dismissed_at` | [alert-auto-dismissed-at](alert-auto-dismissed-at.md) | No |  |
| `dismissal_request` | [dependabot-alert-dismissal-request-simple](dependabot-alert-dismissal-request-simple.md) | No |  |

## Nested Fields

### `dependency`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `package` | [dependabot-alert-package](dependabot-alert-package.md) | No |  |
| `manifest_path` | string | No | The full path to the dependency manifest file, relative to the root of the repository. |
| `scope` | enum: development, runtime | No | The execution scope of the vulnerable dependency. |
| `relationship` | enum: unknown, direct, transitive | No | The vulnerable dependency's relationship to your project.

> [!NOTE]
> We are rolling out support for dependency relationship across ecosystems. This value will be "unknown" for all dependencies in unsupported ecosystems.
 |

