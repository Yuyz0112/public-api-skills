# GET /repos/{owner}/{repo}/stats/contributors

**Resource:** [repos](../resources/repos.md)
**Get all contributor commit activity**
**Operation ID:** `repos/get-contributors-stats`


Returns the `total` number of commits authored by the contributor. In addition, the response includes a Weekly Hash (`weeks` array) with the following information:

*   `w` - Start of the week, given as a [Unix timestamp](https://en.wikipedia.org/wiki/Unix_time).
*   `a` - Number of additions
*   `d` - Number of deletions
*   `c` - Number of commits

> [!NOTE]
> This endpoint will return `0` values for all addition and deletion counts in repositories with 10,000 or more commits.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 202 | (reference) |
| 204 | (reference) |

**Success Response Schema:**

Array of [contributor-activity](../schemas/contributor-activity/contributor-activity.md)

