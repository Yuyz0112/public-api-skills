# POST /repos/{owner}/{repo}/issues/{issue_number}/reactions

**Resource:** [reactions](../resources/reactions.md)
**Create reaction for an issue**
**Operation ID:** `reactions/create-for-issue`

Create a reaction to an [issue](https://docs.github.com/rest/issues/issues#get-an-issue). A response with an HTTP `200` status means that you already added the reaction type to this issue.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 201 | Response |
| 422 | (reference) |

**Success Response Schema:**

[reaction](../schemas/reaction/reaction.md)

