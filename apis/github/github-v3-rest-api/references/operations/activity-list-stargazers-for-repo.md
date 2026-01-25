# GET /repos/{owner}/{repo}/stargazers

**Resource:** [activity](../resources/activity.md)
**List stargazers**
**Operation ID:** `activity/list-stargazers-for-repo`

Lists the people that have starred the repository.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.star+json`**: Includes a timestamp of when the star was created.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

