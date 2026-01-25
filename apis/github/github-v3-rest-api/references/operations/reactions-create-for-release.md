# POST /repos/{owner}/{repo}/releases/{release_id}/reactions

**Resource:** [reactions](../resources/reactions.md)
**Create reaction for a release**
**Operation ID:** `reactions/create-for-release`

Create a reaction to a [release](https://docs.github.com/rest/releases/releases#get-a-release). A response with a `Status: 200 OK` means that you already added the reaction type to this release.

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

