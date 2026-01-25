# TweetCreateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card_uri` | string | No | Card Uri Parameter. This is mutually exclusive from Quote Tweet Id, Poll, Media, and Direct Message Deep Link. |
| `community_id` | [CommunityId](CommunityId.md) | No |  |
| `direct_message_deep_link` | string | No | Link to take the conversation from the public timeline to a private Direct Message. |
| `edit_options` | object | No | Options for editing an existing Post. When provided, this request will edit the specified Post instead of creating a new one. |
| `for_super_followers_only` | boolean | No | Exclusive Tweet for super followers. |
| `geo` | object | No | Place ID being attached to the Tweet for geo location. |
| `media` | object | No | Media information being attached to created Tweet. This is mutually exclusive from Quote Tweet Id, Poll, and Card URI. |
| `nullcast` | boolean | No | Nullcasted (promoted-only) Posts do not appear in the public timeline and are not served to followers. |
| `poll` | object | No | Poll options for a Tweet with a poll. This is mutually exclusive from Media, Quote Tweet Id, and Card URI. |
| `quote_tweet_id` | [TweetId](TweetId.md) | No |  |
| `reply` | object | No | Tweet information of the Tweet being replied to. |
| `reply_settings` | enum: following, mentionedUsers, subscribers... | No | Settings to indicate who can reply to the Tweet. |
| `share_with_followers` | boolean | No | Share community post with followers too. |
| `text` | [TweetText](TweetText.md) | No |  |

## Nested Fields

### `edit_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `previous_post_id` | [TweetId](TweetId.md) | Yes |  |

### `geo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `place_id` | string | No |  |

### `media`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `media_ids` | MediaId[] | Yes | A list of Media Ids to be attached to a created Tweet. |
| `tagged_user_ids` | UserId[] | No | A list of User Ids to be tagged in the media for created Tweet. |

### `poll`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `duration_minutes` | integer (int32) | Yes | Duration of the poll in minutes. |
| `options` | string[] | Yes |  |
| `reply_settings` | enum: following, mentionedUsers, subscribers... | No | Settings to indicate who can reply to the Tweet. |

### `reply`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auto_populate_reply_metadata` | boolean | No | If set to true, reply metadata will be automatically populated. |
| `exclude_reply_user_ids` | UserId[] | No | A list of User Ids to be excluded from the reply Tweet. |
| `in_reply_to_tweet_id` | [TweetId](TweetId.md) | Yes |  |

