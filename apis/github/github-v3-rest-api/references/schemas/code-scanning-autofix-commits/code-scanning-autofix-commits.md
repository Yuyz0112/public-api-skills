# code-scanning-autofix-commits

Commit an autofix for a code scanning alert

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target_ref` | string | No | The Git reference of target branch for the commit. Branch needs to already exist.  For more information, see "[Git References](https://git-scm.com/book/en/v2/Git-Internals-Git-References)" in the Git documentation. |
| `message` | string | No | Commit message to be used. |

