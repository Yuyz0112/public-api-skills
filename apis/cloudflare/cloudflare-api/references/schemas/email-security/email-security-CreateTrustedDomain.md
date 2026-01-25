# email-security_CreateTrustedDomain

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `comments` | string | No |  |
| `is_recent` | boolean | Yes | Select to prevent recently registered domains from triggering a
Suspicious or Malicious disposition. |
| `is_regex` | boolean | Yes |  |
| `is_similarity` | boolean | Yes | Select for partner or other approved domains that have similar
spelling to your connected domains. Prevents listed domains from
triggering a Spoof disposition. |
| `pattern` | string | Yes |  |

