# GET /repos/{owner}/{repo}/stats/participation

**Resource:** [repos](../resources/repos.md)
**Get the weekly commit count**
**Operation ID:** `repos/get-participation-stats`

Returns the total commit counts for the `owner` and total commit counts in `all`. `all` is everyone combined, including the `owner` in the last 52 weeks. If you'd like to get the commit counts for non-owners, you can subtract `owner` from `all`.

The array order is oldest week (index 0) to most recent week.

The most recent week is seven days ago at UTC midnight to today at UTC midnight.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The array order is oldest week (index 0) to most recent week. |
| 404 | (reference) |

**Success Response Schema:**

[participation-stats](../schemas/participation-stats/participation-stats.md)

