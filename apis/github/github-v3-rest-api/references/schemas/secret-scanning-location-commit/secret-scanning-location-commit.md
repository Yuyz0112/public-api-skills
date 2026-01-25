# secret-scanning-location-commit

Represents a 'commit' secret scanning location type. This location type shows that a secret was detected inside a commit to a repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `path` | string | Yes | The file path in the repository |
| `start_line` | number | Yes | Line number at which the secret starts in the file |
| `end_line` | number | Yes | Line number at which the secret ends in the file |
| `start_column` | number | Yes | The column at which the secret starts within the start line when the file is interpreted as 8BIT ASCII |
| `end_column` | number | Yes | The column at which the secret ends within the end line when the file is interpreted as 8BIT ASCII |
| `blob_sha` | string | Yes | SHA-1 hash ID of the associated blob |
| `blob_url` | string | Yes | The API URL to get the associated blob resource |
| `commit_sha` | string | Yes | SHA-1 hash ID of the associated commit |
| `commit_url` | string | Yes | The API URL to get the associated commit resource |

