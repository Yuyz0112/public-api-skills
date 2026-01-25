# pages-https-certificate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `state` | enum: new, authorization_created, authorization_pending... | Yes |  |
| `description` | string | Yes |  |
| `domains` | string[] | Yes | Array of the domain set and its alternate name (if it is configured) |
| `expires_at` | string (date) | No |  |

