# DELETE /2/notes/{id}

**Resource:** [Community Notes](../resources/Community-Notes.md)
**Delete a Community Note**
**Operation ID:** `deleteCommunityNotes`

Deletes a community note.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | NoteId | Yes | The community note id to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[DeleteNoteResponse](../schemas/Delete/DeleteNoteResponse.md)

## Security

- **OAuth2UserToken**: tweet.write
- **UserToken**
