# import

A repository import from an external source.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `vcs` | string | Yes |  |
| `use_lfs` | boolean | No |  |
| `vcs_url` | string | Yes | The URL of the originating repository. |
| `svc_root` | string | No |  |
| `tfvc_project` | string | No |  |
| `status` | enum: auth, error, none... | Yes |  |
| `status_text` | string | No |  |
| `failed_step` | string | No |  |
| `error_message` | string | No |  |
| `import_percent` | integer | No |  |
| `commit_count` | integer | No |  |
| `push_percent` | integer | No |  |
| `has_large_files` | boolean | No |  |
| `large_files_size` | integer | No |  |
| `large_files_count` | integer | No |  |
| `project_choices` | object[] | No |  |
| `message` | string | No |  |
| `authors_count` | integer | No |  |
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `authors_url` | string (uri) | Yes |  |
| `repository_url` | string (uri) | Yes |  |
| `svn_root` | string | No |  |

## Nested Fields

### `project_choices`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `vcs` | string | No |  |
| `tfvc_project` | string | No |  |
| `human_name` | string | No |  |

