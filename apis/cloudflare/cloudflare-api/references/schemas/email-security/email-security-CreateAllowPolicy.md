# email-security_CreateAllowPolicy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `comments` | string | No |  |
| `is_acceptable_sender` | boolean | Yes | Messages from this sender will be exempted from Spam, Spoof and Bulk dispositions.
Note: This will not exempt messages with Malicious or Suspicious dispositions. |
| `is_exempt_recipient` | boolean | Yes | Messages to this recipient will bypass all detections. |
| `is_recipient` | boolean | No |  |
| `is_regex` | boolean | Yes |  |
| `is_sender` | boolean | No |  |
| `is_spoof` | boolean | No |  |
| `is_trusted_sender` | boolean | Yes | Messages from this sender will bypass all detections and link following. |
| `pattern` | string | Yes |  |
| `pattern_type` | [email-security_PatternType](email-security-PatternType.md) | Yes |  |
| `verify_sender` | boolean | Yes | Enforce DMARC, SPF or DKIM authentication.
When on, Email Security only honors policies that pass authentication. |

