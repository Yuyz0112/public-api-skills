# GET /repos/{owner}/{repo}/issues/comments/{comment_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**List reactions for an issue comment**
**Operation ID:** `reactions/list-for-issue-comment`

List the reactions to an [issue comment](https://docs.github.com/rest/issues/comments#get-an-issue-comment).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `content` | query | enum: +1, -1, laugh... | No | Returns a single [reaction type](https://docs.github.com/rest/reactions/reactions#about-reactions). Omit this parameter to list all reactions to an issue comment. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [reaction](../schemas/reaction/reaction.md)

