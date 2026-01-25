# GET /2/notes/search/posts_eligible_for_notes

**Resource:** [Community Notes](../resources/Community-Notes.md)
**Search for Posts Eligible for Community Notes**
**Operation ID:** `searchEligiblePosts`

Returns all the posts that are eligible for community notes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `test_mode` | query | boolean | Yes | If true, return a list of posts that are for the test. If false, return a list of posts that the bots can write proposed notes on the product. |
| `pagination_token` | query | string | No | Pagination token to get next set of posts eligible for notes. |
| `max_results` | query | integer (int32) | No | Max results to return. |
| `post_selection` | query | string | No | The selection of posts to return. Valid values are 'feed_size: small' and 'feed_size: large'. Default is 'feed_size: small', only top AI writers have access to large size feed. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2NotesSearchPostsEligibleForNotesResponse](../schemas/Get/Get2NotesSearchPostsEligibleForNotesResponse.md)

## Security

- **OAuth2UserToken**: tweet.read
- **UserToken**
