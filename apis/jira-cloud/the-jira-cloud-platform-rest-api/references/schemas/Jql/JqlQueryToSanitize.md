# JqlQueryToSanitize

The JQL query to sanitize for the account ID. If the account ID is null, sanitizing is performed for an anonymous user.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountId` | string | No | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |
| `query` | string | Yes | The query to sanitize. |

