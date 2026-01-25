# GET /repos/{owner}/{repo}/stats/punch_card

**Resource:** [repos](../resources/repos.md)
**Get the hourly commit count for each day**
**Operation ID:** `repos/get-punch-card-stats`

Each array contains the day number, hour number, and number of commits:

*   `0-6`: Sunday - Saturday
*   `0-23`: Hour of day
*   Number of commits

For example, `[2, 14, 25]` indicates that there were 25 total commits, during the 2:00pm hour on Tuesdays. All times are based on the time zone of individual commits.

## Responses

| Status | Description |
|--------|-------------|
| 200 | For example, `[2, 14, 25]` indicates that there were 25 total commits, during the 2:00pm hour on Tuesdays. All times are based on the time zone of individual commits. |
| 204 | (reference) |

**Success Response Schema:**

Array of [code-frequency-stat](../schemas/code-frequency-stat/code-frequency-stat.md)

