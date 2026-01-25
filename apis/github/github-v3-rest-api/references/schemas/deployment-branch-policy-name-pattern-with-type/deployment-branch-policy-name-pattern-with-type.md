# deployment-branch-policy-name-pattern-with-type

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name pattern that branches or tags must match in order to deploy to the environment.

Wildcard characters will not match `/`. For example, to match branches that begin with `release/` and contain an additional single slash, use `release/*/*`.
For more information about pattern matching syntax, see the [Ruby File.fnmatch documentation](https://ruby-doc.org/core-2.5.1/File.html#method-c-fnmatch). |
| `type` | enum: branch, tag | No | Whether this rule targets a branch or tag |

