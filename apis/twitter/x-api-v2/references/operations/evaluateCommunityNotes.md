# POST /2/evaluate_note

**Resource:** [Community Notes](../resources/Community-Notes.md)
**Evaluate a Community Note**
**Operation ID:** `evaluateCommunityNotes`

Endpoint to evaluate a community note.

## Request Body

**Content Types:** `application/json`

**Schema:** [EvaluateNoteRequest](../schemas/Evaluate/EvaluateNoteRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[EvaluateNoteResponse](../schemas/Evaluate/EvaluateNoteResponse.md)

## Security

- **OAuth2UserToken**: tweet.write
- **UserToken**
