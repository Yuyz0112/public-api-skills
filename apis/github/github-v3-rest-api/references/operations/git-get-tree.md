# GET /repos/{owner}/{repo}/git/trees/{tree_sha}

**Resource:** [git](../resources/git.md)
**Get a tree**
**Operation ID:** `git/get-tree`

Returns a single tree using the SHA1 value or ref name for that tree.

If `truncated` is `true` in the response then the number of items in the `tree` array exceeded our maximum limit. If you need to fetch more items, use the non-recursive method of fetching trees, and fetch one sub-tree at a time.

> [!NOTE]
> The limit for the `tree` array is 100,000 entries with a maximum size of 7 MB when using the `recursive` parameter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tree_sha` | path | string | Yes | The SHA1 value or ref (branch or tag) name of the tree. |
| `recursive` | query | string | No | Setting this parameter to any value returns the objects or subtrees referenced by the tree specified in `:tree_sha`. For example, setting `recursive` to any of the following will enable returning objects or subtrees: `0`, `1`, `"true"`, and `"false"`. Omit this parameter to prevent recursively returning objects or subtrees. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[git-tree](../schemas/git-tree/git-tree.md)

