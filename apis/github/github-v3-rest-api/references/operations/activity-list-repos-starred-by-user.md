# GET /users/{username}/starred

**Resource:** [activity](../resources/activity.md)
**List repositories starred by a user**
**Operation ID:** `activity/list-repos-starred-by-user`

Lists repositories a user has starred.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.star+json`**: Includes a timestamp of when the star was created.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

