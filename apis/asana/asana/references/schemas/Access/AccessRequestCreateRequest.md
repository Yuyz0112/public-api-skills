# AccessRequestCreateRequest

A request to create shareable access for a user.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | string | Yes | The access requestable object that the user is requesting access to. This is the gid of the target. Supports projects and portfolios. |
| `message` | string | No | The optional message to include with the access request. This can be used to provide context or additional information about the request. |

