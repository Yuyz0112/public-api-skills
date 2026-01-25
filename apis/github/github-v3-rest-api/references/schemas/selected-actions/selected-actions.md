# selected-actions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `github_owned_allowed` | boolean | No | Whether GitHub-owned actions are allowed. For example, this includes the actions in the `actions` organization. |
| `verified_allowed` | boolean | No | Whether actions from GitHub Marketplace verified creators are allowed. Set to `true` to allow all actions by GitHub Marketplace verified creators. |
| `patterns_allowed` | string[] | No | Specifies a list of string-matching patterns to allow specific action(s) and reusable workflow(s). Wildcards, tags, and SHAs are allowed. For example, `monalisa/octocat@*`, `monalisa/octocat@v2`, `monalisa/*`.

> [!NOTE]
> The `patterns_allowed` setting only applies to public repositories. |

