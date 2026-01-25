# User

The X User object.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `affiliation` | object | No | Metadata about a user's affiliation. |
| `connection_status` | string[] | No | Returns detailed information about the relationship between two users. |
| `created_at` | string (date-time) | No | Creation time of this User. |
| `description` | string | No | The text of this User's profile description (also known as bio), if the User provided one. |
| `entities` | object | No | A list of metadata found in the User's profile description. |
| `id` | [UserId](UserId.md) | Yes |  |
| `location` | string | No | The location specified in the User's profile, if the User provided one. As this is a freeform value, it may not indicate a valid location, but it may be fuzzily evaluated when performing searches with location queries. |
| `most_recent_tweet_id` | [TweetId](TweetId.md) | No |  |
| `name` | string | Yes | The friendly name of this User, as shown on their profile. |
| `pinned_tweet_id` | [TweetId](TweetId.md) | No |  |
| `profile_banner_url` | string (uri) | No | The URL to the profile banner for this User. |
| `profile_image_url` | string (uri) | No | The URL to the profile image for this User. |
| `protected` | boolean | No | Indicates if this User has chosen to protect their Posts (in other words, if this User's Posts are private). |
| `public_metrics` | object | No | A list of metrics for this User. |
| `receives_your_dm` | boolean | No | Indicates if you can send a DM to this User |
| `subscription_type` | enum: Basic, Premium, PremiumPlus... | No | The X Blue subscription type of the user, eg: Basic, Premium, PremiumPlus or None. |
| `url` | string | No | The URL specified in the User's profile. |
| `username` | [UserName](UserName.md) | Yes |  |
| `verified` | boolean | No | Indicate if this User is a verified X User. |
| `verified_type` | enum: blue, government, business... | No | The X Blue verified type of the user, eg: blue, government, business or none. |
| `withheld` | [UserWithheld](UserWithheld.md) | No |  |

## Nested Fields

### `affiliation`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `badge_url` | string (uri) | No | The badge URL corresponding to the affiliation. |
| `description` | string | No | The description of the affiliation. |
| `url` | string (uri) | No | The URL, if available, to details about an affiliation. |
| `user_id` | UserId[] | No |  |

### `entities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | [FullTextEntities](FullTextEntities.md) | No |  |
| `url` | object | No | Expanded details for the URL specified in the User's profile, with start and end indices. |

#### `entities.url`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `urls` | UrlEntity[] | No |  |

### `public_metrics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `followers_count` | integer | Yes | Number of Users who are following this User. |
| `following_count` | integer | Yes | Number of Users this User is following. |
| `like_count` | integer | No | The number of likes created by this User. |
| `listed_count` | integer | Yes | The number of lists that include this User. |
| `tweet_count` | integer | Yes | The number of Posts (including Retweets) posted by this User. |

