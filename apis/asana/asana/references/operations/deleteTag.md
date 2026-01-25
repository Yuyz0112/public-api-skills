# DELETE /tags/{tag_gid}

**Resource:** [Tags](../resources/Tags.md)
**Delete a tag**
**Operation ID:** `deleteTag`

A specific, existing tag can be deleted by making a DELETE request on
the URL for that tag.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified tag. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
