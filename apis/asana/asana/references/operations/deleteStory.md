# DELETE /stories/{story_gid}

**Resource:** [Stories](../resources/Stories.md)
**Delete a story**
**Operation ID:** `deleteStory`

Deletes a story. A user can only delete stories they have created.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified story. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
