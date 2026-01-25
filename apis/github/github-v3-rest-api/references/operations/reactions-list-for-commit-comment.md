# GET /repos/{owner}/{repo}/comments/{comment_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**List reactions for a commit comment**
**Operation ID:** `reactions/list-for-commit-comment`

List the reactions to a [commit comment](https://docs.github.com/rest/commits/comments#get-a-commit-comment).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `content` | query | enum: +1, -1, laugh... | No | Returns a single [reaction type](https://docs.github.com/rest/reactions/reactions#about-reactions). Omit this parameter to list all reactions to a commit comment. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [reaction](../schemas/reaction/reaction.md)

