# GET /repos/{owner}/{repo}/pulls/comments/{comment_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**List reactions for a pull request review comment**
**Operation ID:** `reactions/list-for-pull-request-review-comment`

List the reactions to a [pull request review comment](https://docs.github.com/rest/pulls/comments#get-a-review-comment-for-a-pull-request).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `content` | query | enum: +1, -1, laugh... | No | Returns a single [reaction type](https://docs.github.com/rest/reactions/reactions#about-reactions). Omit this parameter to list all reactions to a pull request review comment. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [reaction](../schemas/reaction/reaction.md)

