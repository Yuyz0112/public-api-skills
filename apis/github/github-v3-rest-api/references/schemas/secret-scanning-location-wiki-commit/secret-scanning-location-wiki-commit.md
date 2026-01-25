# secret-scanning-location-wiki-commit

Represents a 'wiki_commit' secret scanning location type. This location type shows that a secret was detected inside a commit to a repository wiki.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `path` | string | Yes | The file path of the wiki page |
| `start_line` | number | Yes | Line number at which the secret starts in the file |
| `end_line` | number | Yes | Line number at which the secret ends in the file |
| `start_column` | number | Yes | The column at which the secret starts within the start line when the file is interpreted as 8-bit ASCII. |
| `end_column` | number | Yes | The column at which the secret ends within the end line when the file is interpreted as 8-bit ASCII. |
| `blob_sha` | string | Yes | SHA-1 hash ID of the associated blob |
| `page_url` | string | Yes | The GitHub URL to get the associated wiki page |
| `commit_sha` | string | Yes | SHA-1 hash ID of the associated commit |
| `commit_url` | string | Yes | The GitHub URL to get the associated wiki commit |

