# commit-comparison

Commit Comparison

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `permalink_url` | string (uri) | Yes |  |
| `diff_url` | string (uri) | Yes |  |
| `patch_url` | string (uri) | Yes |  |
| `base_commit` | [commit](commit.md) | Yes |  |
| `merge_base_commit` | [commit](commit.md) | Yes |  |
| `status` | enum: diverged, ahead, behind... | Yes |  |
| `ahead_by` | integer | Yes |  |
| `behind_by` | integer | Yes |  |
| `total_commits` | integer | Yes |  |
| `commits` | commit[] | Yes |  |
| `files` | diff-entry[] | No |  |

