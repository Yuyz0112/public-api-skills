# secret-scanning-location-pull-request-body

Represents a 'pull_request_body' secret scanning location type. This location type shows that a secret was detected in the body of a pull request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pull_request_body_url` | string (uri) | Yes | The API URL to get the pull request where the secret was detected. |

