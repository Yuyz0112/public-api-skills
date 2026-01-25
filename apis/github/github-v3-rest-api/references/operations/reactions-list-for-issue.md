# GET /repos/{owner}/{repo}/issues/{issue_number}/reactions

**Resource:** [reactions](../resources/reactions.md)
**List reactions for an issue**
**Operation ID:** `reactions/list-for-issue`

List the reactions to an [issue](https://docs.github.com/rest/issues/issues#get-an-issue).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `content` | query | enum: +1, -1, laugh... | No | Returns a single [reaction type](https://docs.github.com/rest/reactions/reactions#about-reactions). Omit this parameter to list all reactions to an issue. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

Array of [reaction](../schemas/reaction/reaction.md)

