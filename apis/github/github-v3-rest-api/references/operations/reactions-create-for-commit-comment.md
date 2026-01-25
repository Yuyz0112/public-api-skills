# POST /repos/{owner}/{repo}/comments/{comment_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**Create reaction for a commit comment**
**Operation ID:** `reactions/create-for-commit-comment`

Create a reaction to a [commit comment](https://docs.github.com/rest/commits/comments#get-a-commit-comment). A response with an HTTP `200` status means that you already added the reaction type to this commit comment.

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

