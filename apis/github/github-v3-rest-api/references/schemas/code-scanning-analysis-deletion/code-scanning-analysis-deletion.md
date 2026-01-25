# code-scanning-analysis-deletion

Successful deletion of a code scanning analysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `next_analysis_url` | string (uri) | Yes | Next deletable analysis in chain, without last analysis deletion confirmation |
| `confirm_delete_url` | string (uri) | Yes | Next deletable analysis in chain, with last analysis deletion confirmation |

