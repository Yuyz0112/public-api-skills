# merge-group

A group of pull requests that the merge queue has grouped together to be merged.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `head_sha` | string | Yes | The SHA of the merge group. |
| `head_ref` | string | Yes | The full ref of the merge group. |
| `base_sha` | string | Yes | The SHA of the merge group's parent commit. |
| `base_ref` | string | Yes | The full ref of the branch the merge group will be merged into. |
| `head_commit` | [simple-commit](simple-commit.md) | Yes |  |

