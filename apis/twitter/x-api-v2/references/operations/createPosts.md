# POST /2/tweets

**Resource:** [Tweets](../resources/Tweets.md)
**Create or Edit Post**
**Operation ID:** `createPosts`

Creates a new Post for the authenticated user, or edits an existing Post when edit_options are provided.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [TweetCreateRequest](../schemas/Tweet/TweetCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[TweetCreateResponse](../schemas/Tweet/TweetCreateResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, tweet.write, users.read
- **UserToken**
