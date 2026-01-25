# POST /repos/{owner}/{repo}/issues/comments/{comment_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**Create reaction for an issue comment**
**Operation ID:** `reactions/create-for-issue-comment`

Create a reaction to an [issue comment](https://docs.github.com/rest/issues/comments#get-an-issue-comment). A response with an HTTP `200` status means that you already added the reaction type to this issue comment.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Reaction exists |
| 201 | Reaction created |
| 422 | (reference) |

**Success Response Schema:**

[reaction](../schemas/reaction/reaction.md)

