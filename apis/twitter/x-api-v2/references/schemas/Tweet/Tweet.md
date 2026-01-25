# Tweet

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `attachments` | object | No | Specifies the type of attachments (if any) present in this Tweet. |
| `author_id` | [UserId](UserId.md) | No |  |
| `community_id` | [CommunityId](CommunityId.md) | No |  |
| `context_annotations` | ContextAnnotation[] | No |  |
| `conversation_id` | [TweetId](TweetId.md) | No |  |
| `created_at` | string (date-time) | No | Creation time of the Tweet. |
| `display_text_range` | [DisplayTextRange](DisplayTextRange.md) | No |  |
| `edit_controls` | object | No |  |
| `edit_history_tweet_ids` | TweetId[] | No | A list of Tweet Ids in this Tweet chain. |
| `entities` | [FullTextEntities](FullTextEntities.md) | No |  |
| `geo` | object | No | The location tagged on the Tweet, if the user provided one. |
| `id` | [TweetId](TweetId.md) | No |  |
| `in_reply_to_user_id` | [UserId](UserId.md) | No |  |
| `lang` | string | No | Language of the Tweet, if detected by X. Returned as a BCP47 language tag. |
| `non_public_metrics` | object | No | Nonpublic engagement metrics for the Tweet at the time of the request. |
| `note_tweet` | object | No | The full-content of the Tweet, including text beyond 280 characters. |
| `organic_metrics` | object | No | Organic nonpublic engagement metrics for the Tweet at the time of the request. |
| `possibly_sensitive` | boolean | No | Indicates if this Tweet contains URLs marked as sensitive, for example content suitable for mature audiences. |
| `promoted_metrics` | object | No | Promoted nonpublic engagement metrics for the Tweet at the time of the request. |
| `public_metrics` | object | No | Engagement metrics for the Tweet at the time of the request. |
| `referenced_tweets` | object[] | No | A list of Posts this Tweet refers to. For example, if the parent Tweet is a Retweet, a Quoted Tweet or a Reply, it will include the related Tweet referenced to by its parent. |
| `reply_settings` | [ReplySettingsWithVerifiedUsers](ReplySettingsWithVerifiedUsers.md) | No |  |
| `scopes` | object | No | The scopes for this tweet |
| `source` | string | No | This is deprecated. |
| `suggested_source_links` | UrlEntity[] | No |  |
| `suggested_source_links_with_counts` | object | No | Suggested source links and the number of requests that included each link. |
| `text` | [TweetText](TweetText.md) | No |  |
| `username` | [UserName](UserName.md) | No |  |
| `withheld` | [TweetWithheld](TweetWithheld.md) | No |  |

## Nested Fields

### `attachments`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `media_keys` | MediaKey[] | No | A list of Media Keys for each one of the media attachments (if media are attached). |
| `media_source_tweet_id` | TweetId[] | No | A list of Posts the media on this Tweet was originally posted in. For example, if the media on a tweet is re-used in another Tweet, this refers to the original, source Tweet.. |
| `poll_ids` | PollId[] | No | A list of poll IDs (if polls are attached). |

### `edit_controls`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editable_until` | string (date-time) | Yes | Time when Tweet is no longer editable. |
| `edits_remaining` | integer | Yes | Number of times this Tweet can be edited. |
| `is_edit_eligible` | boolean | Yes | Indicates if this Tweet is eligible to be edited. |

### `geo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `coordinates` | [Point](Point.md) | No |  |
| `place_id` | [PlaceId](PlaceId.md) | No |  |

### `non_public_metrics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `impression_count` | integer (int32) | No | Number of times this Tweet has been viewed. |

### `note_tweet`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `entities` | object | No |  |
| `text` | [NoteTweetText](NoteTweetText.md) | No |  |

#### `note_tweet.entities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cashtags` | CashtagEntity[] | No |  |
| `hashtags` | HashtagEntity[] | No |  |
| `mentions` | MentionEntity[] | No |  |
| `urls` | UrlEntity[] | No |  |

### `organic_metrics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `impression_count` | integer | Yes | Number of times this Tweet has been viewed. |
| `like_count` | integer | Yes | Number of times this Tweet has been liked. |
| `reply_count` | integer | Yes | Number of times this Tweet has been replied to. |
| `retweet_count` | integer | Yes | Number of times this Tweet has been Retweeted. |

### `promoted_metrics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `impression_count` | integer (int32) | No | Number of times this Tweet has been viewed. |
| `like_count` | integer (int32) | No | Number of times this Tweet has been liked. |
| `reply_count` | integer (int32) | No | Number of times this Tweet has been replied to. |
| `retweet_count` | integer (int32) | No | Number of times this Tweet has been Retweeted. |

### `public_metrics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bookmark_count` | integer (int32) | Yes | Number of times this Tweet has been bookmarked. |
| `impression_count` | integer (int32) | Yes | Number of times this Tweet has been viewed. |
| `like_count` | integer | Yes | Number of times this Tweet has been liked. |
| `quote_count` | integer | No | Number of times this Tweet has been quoted. |
| `reply_count` | integer | Yes | Number of times this Tweet has been replied to. |
| `retweet_count` | integer | Yes | Number of times this Tweet has been Retweeted. |

### `referenced_tweets`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [TweetId](TweetId.md) | Yes |  |
| `type` | enum: retweeted, quoted, replied_to | Yes |  |

### `scopes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `followers` | boolean | No | Indicates if this Tweet is viewable by followers without the Tweet ID |

### `suggested_source_links_with_counts`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | No | Number of note requests that included the source link. |
| `url` | [UrlEntity](UrlEntity.md) | No |  |

