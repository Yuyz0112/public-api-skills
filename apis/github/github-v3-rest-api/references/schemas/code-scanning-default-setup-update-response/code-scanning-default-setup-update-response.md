# code-scanning-default-setup-update-response

You can use `run_url` to track the status of the run. This includes a property status and conclusion.
You should not rely on this always being an actions workflow run object.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `run_id` | integer | No | ID of the corresponding run. |
| `run_url` | string | No | URL of the corresponding run. |

