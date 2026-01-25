# repository-advisory-credit

A credit given to a user for a repository security advisory.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `user` | [simple-user](simple-user.md) | Yes |  |
| `type` | [security-advisory-credit-types](security-advisory-credit-types.md) | Yes |  |
| `state` | enum: accepted, declined, pending | Yes | The state of the user's acceptance of the credit. |

