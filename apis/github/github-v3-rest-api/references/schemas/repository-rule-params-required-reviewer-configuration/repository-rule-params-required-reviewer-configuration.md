# repository-rule-params-required-reviewer-configuration

A reviewing team, and file patterns describing which files they must approve changes to.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `file_patterns` | string[] | Yes | Array of file patterns. Pull requests which change matching files must be approved by the specified team. File patterns use fnmatch syntax. |
| `minimum_approvals` | integer | Yes | Minimum number of approvals required from the specified team. If set to zero, the team will be added to the pull request but approval is optional. |
| `reviewer` | [repository-rule-params-reviewer](repository-rule-params-reviewer.md) | Yes |  |

