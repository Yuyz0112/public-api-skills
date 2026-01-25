# POST /2/notes

**Resource:** [Community Notes](../resources/Community-Notes.md)
**Create a Community Note**
**Operation ID:** `createCommunityNotes`

Creates a community note endpoint for LLM use case.

## Request Body

**Content Types:** `application/json`

**Schema:** [CreateNoteRequest](../schemas/Create/CreateNoteRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[CreateNoteResponse](../schemas/Create/CreateNoteResponse.md)

## Security

- **OAuth2UserToken**: tweet.write
- **UserToken**
