# GET /user/starred

**Resource:** [activity](../resources/activity.md)
**List repositories starred by the authenticated user**
**Operation ID:** `activity/list-repos-starred-by-authenticated-user`

Lists repositories the authenticated user has starred.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.star+json`**: Includes a timestamp of when the star was created.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [repository](../schemas/repository/repository.md)

