# Tweets

Endpoints related to retrieving, searching, and modifying Tweets

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/2/insights/28hr` | Get 28-hour Post insights | [View](../operations/getInsights28Hr.md) |
| GET | `/2/insights/historical` | Get historical Post insights | [View](../operations/getInsightsHistorical.md) |
| GET | `/2/lists/{id}/tweets` | Get List Posts | [View](../operations/getListsPosts.md) |
| GET | `/2/spaces/{id}/buyers` | Get Space ticket buyers | [View](../operations/getSpacesBuyers.md) |
| GET | `/2/spaces/{id}/tweets` | Get Space Posts | [View](../operations/getSpacesPosts.md) |
| GET | `/2/tweets` | Get Posts by IDs | [View](../operations/getPostsByIds.md) |
| POST | `/2/tweets` | Create or Edit Post | [View](../operations/createPosts.md) |
| GET | `/2/tweets/analytics` | Get Post analytics | [View](../operations/getPostsAnalytics.md) |
| GET | `/2/tweets/counts/all` | Get count of all Posts | [View](../operations/getPostsCountsAll.md) |
| GET | `/2/tweets/counts/recent` | Get count of recent Posts | [View](../operations/getPostsCountsRecent.md) |
| GET | `/2/tweets/firehose/stream` | Stream all Posts | [View](../operations/streamPostsFirehose.md) |
| GET | `/2/tweets/firehose/stream/lang/en` | Stream English Posts | [View](../operations/streamPostsFirehoseEn.md) |
| GET | `/2/tweets/firehose/stream/lang/ja` | Stream Japanese Posts | [View](../operations/streamPostsFirehoseJa.md) |
| GET | `/2/tweets/firehose/stream/lang/ko` | Stream Korean Posts | [View](../operations/streamPostsFirehoseKo.md) |
| GET | `/2/tweets/firehose/stream/lang/pt` | Stream Portuguese Posts | [View](../operations/streamPostsFirehosePt.md) |
| GET | `/2/tweets/sample/stream` | Stream sampled Posts | [View](../operations/streamPostsSample.md) |
| GET | `/2/tweets/sample10/stream` | Stream 10% sampled Posts | [View](../operations/streamPostsSample10.md) |
| GET | `/2/tweets/search/all` | Search all Posts | [View](../operations/searchPostsAll.md) |
| GET | `/2/tweets/search/recent` | Search recent Posts | [View](../operations/searchPostsRecent.md) |
| GET | `/2/tweets/search/stream` | Stream filtered Posts | [View](../operations/streamPosts.md) |
| GET | `/2/tweets/search/stream/rules` | Get stream rules | [View](../operations/getRules.md) |
| POST | `/2/tweets/search/stream/rules` | Update stream rules | [View](../operations/updateRules.md) |
| GET | `/2/tweets/search/stream/rules/counts` | Get stream rule counts | [View](../operations/getRuleCounts.md) |
| GET | `/2/tweets/{id}` | Get Post by ID | [View](../operations/getPostsById.md) |
| DELETE | `/2/tweets/{id}` | Delete Post | [View](../operations/deletePosts.md) |
| GET | `/2/tweets/{id}/liking_users` | Get Liking Users | [View](../operations/getPostsLikingUsers.md) |
| GET | `/2/tweets/{id}/quote_tweets` | Get Quoted Posts | [View](../operations/getPostsQuotedPosts.md) |
| GET | `/2/tweets/{id}/retweeted_by` | Get Reposted by | [View](../operations/getPostsRepostedBy.md) |
| GET | `/2/tweets/{id}/retweets` | Get Reposts | [View](../operations/getPostsReposts.md) |
| PUT | `/2/tweets/{tweet_id}/hidden` | Hide reply | [View](../operations/hidePostsReply.md) |
| GET | `/2/users/{id}/liked_tweets` | Get liked Posts | [View](../operations/getUsersLikedPosts.md) |
| POST | `/2/users/{id}/likes` | Like Post | [View](../operations/likePost.md) |
| DELETE | `/2/users/{id}/likes/{tweet_id}` | Unlike Post | [View](../operations/unlikePost.md) |
| GET | `/2/users/{id}/mentions` | Get mentions | [View](../operations/getUsersMentions.md) |
| POST | `/2/users/{id}/retweets` | Repost Post | [View](../operations/repostPost.md) |
| DELETE | `/2/users/{id}/retweets/{source_tweet_id}` | Unrepost Post | [View](../operations/unrepostPost.md) |
| GET | `/2/users/{id}/timelines/reverse_chronological` | Get Timeline | [View](../operations/getUsersTimeline.md) |
| GET | `/2/users/{id}/tweets` | Get Posts | [View](../operations/getUsersPosts.md) |
