# POST /repos/{owner}/{repo}/pulls/comments/{comment_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**Create reaction for a pull request review comment**
**Operation ID:** `reactions/create-for-pull-request-review-comment`

Create a reaction to a [pull request review comment](https://docs.github.com/rest/pulls/comments#get-a-review-comment-for-a-pull-request). A response with an HTTP `200` status means that you already added the reaction type to this pull request review comment.

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

