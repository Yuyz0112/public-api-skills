# DeprecatedPortfolioMembershipCompact

This object determines if a user is a member of a portfolio.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `portfolio` | [PortfolioCompact](PortfolioCompact.md) | No |  |
| `user` | [UserCompact](UserCompact.md) | No |  |
| `access_level` | enum: admin, editor, viewer | No | Whether the member has admin, editor, or viewer access to the portfolio. Portfolios do not support commenter access yet. |

