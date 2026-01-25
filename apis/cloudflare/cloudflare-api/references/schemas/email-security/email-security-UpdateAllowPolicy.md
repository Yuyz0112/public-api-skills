# email-security_UpdateAllowPolicy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `comments` | string | No |  |
| `is_acceptable_sender` | boolean | No | Messages from this sender will be exempted from Spam, Spoof and Bulk dispositions.
Note: This will not exempt messages with Malicious or Suspicious dispositions. |
| `is_exempt_recipient` | boolean | No | Messages to this recipient will bypass all detections. |
| `is_regex` | boolean | No |  |
| `is_trusted_sender` | boolean | No | Messages from this sender will bypass all detections and link following. |
| `pattern` | string | No |  |
| `pattern_type` | any | No |  |
| `verify_sender` | boolean | No | Enforce DMARC, SPF or DKIM authentication.
When on, Email Security only honors policies that pass authentication. |

