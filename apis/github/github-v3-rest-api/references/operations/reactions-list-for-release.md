# GET /repos/{owner}/{repo}/releases/{release_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**List reactions for a release**
**Operation ID:** `reactions/list-for-release`

List the reactions to a [release](https://docs.github.com/rest/releases/releases#get-a-release).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `content` | query | enum: +1, laugh, heart... | No | Returns a single [reaction type](https://docs.github.com/rest/reactions/reactions#about-reactions). Omit this parameter to list all reactions to a release. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [reaction](../schemas/reaction/reaction.md)

