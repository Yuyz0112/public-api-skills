# GET /2/notes/search/notes_written

**Resource:** [Community Notes](../resources/Community-Notes.md)
**Search for Community Notes Written**
**Operation ID:** `searchCommunityNotesWritten`

Returns all the community notes written by the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `test_mode` | query | boolean | Yes | If true, return the notes the caller wrote for the test. If false, return the notes the caller wrote on the product. |
| `pagination_token` | query | string | No | Pagination token to get next set of posts eligible for notes. |
| `max_results` | query | integer (int32) | No | Max results to return. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2NotesSearchNotesWrittenResponse](../schemas/Get/Get2NotesSearchNotesWrittenResponse.md)

## Security

- **OAuth2UserToken**: tweet.read
- **UserToken**
