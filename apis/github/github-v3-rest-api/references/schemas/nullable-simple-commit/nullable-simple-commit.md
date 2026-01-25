# nullable-simple-commit

A commit.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | SHA for the commit |
| `tree_id` | string | Yes | SHA for the commit's tree |
| `message` | string | Yes | Message describing the purpose of the commit |
| `timestamp` | string (date-time) | Yes | Timestamp of the commit |
| `author` | object | Yes | Information about the Git author |
| `committer` | object | Yes | Information about the Git committer |

## Nested Fields

### `author`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the commit's author |
| `email` | string (email) | Yes | Git email address of the commit's author |

### `committer`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the commit's committer |
| `email` | string (email) | Yes | Git email address of the commit's committer |

