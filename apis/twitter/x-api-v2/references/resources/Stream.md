# Stream

Endpoints related to streaming

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/2/activity/stream` | Activity Stream | [View](../operations/activityStream.md) |
| POST | `/2/activity/subscriptions` | Create X activity subscription | [View](../operations/createActivitySubscription.md) |
| GET | `/2/likes/compliance/stream` | Stream Likes compliance data | [View](../operations/streamLikesCompliance.md) |
| GET | `/2/likes/firehose/stream` | Stream all Likes | [View](../operations/streamLikesFirehose.md) |
| GET | `/2/likes/sample10/stream` | Stream sampled Likes | [View](../operations/streamLikesSample10.md) |
| GET | `/2/tweets/compliance/stream` | Stream Posts compliance data | [View](../operations/streamPostsCompliance.md) |
| GET | `/2/tweets/firehose/stream` | Stream all Posts | [View](../operations/streamPostsFirehose.md) |
| GET | `/2/tweets/firehose/stream/lang/en` | Stream English Posts | [View](../operations/streamPostsFirehoseEn.md) |
| GET | `/2/tweets/firehose/stream/lang/ja` | Stream Japanese Posts | [View](../operations/streamPostsFirehoseJa.md) |
| GET | `/2/tweets/firehose/stream/lang/ko` | Stream Korean Posts | [View](../operations/streamPostsFirehoseKo.md) |
| GET | `/2/tweets/firehose/stream/lang/pt` | Stream Portuguese Posts | [View](../operations/streamPostsFirehosePt.md) |
| GET | `/2/tweets/label/stream` | Stream Post labels | [View](../operations/streamLabelsCompliance.md) |
| GET | `/2/tweets/sample/stream` | Stream sampled Posts | [View](../operations/streamPostsSample.md) |
| GET | `/2/tweets/sample10/stream` | Stream 10% sampled Posts | [View](../operations/streamPostsSample10.md) |
| GET | `/2/tweets/search/stream` | Stream filtered Posts | [View](../operations/streamPosts.md) |
| GET | `/2/tweets/search/stream/rules` | Get stream rules | [View](../operations/getRules.md) |
| POST | `/2/tweets/search/stream/rules` | Update stream rules | [View](../operations/updateRules.md) |
| GET | `/2/tweets/search/stream/rules/counts` | Get stream rule counts | [View](../operations/getRuleCounts.md) |
| GET | `/2/tweets/search/webhooks` | Get stream links | [View](../operations/getWebhooksStreamLinks.md) |
| POST | `/2/tweets/search/webhooks/{webhook_id}` | Create stream link | [View](../operations/createWebhooksStreamLink.md) |
| DELETE | `/2/tweets/search/webhooks/{webhook_id}` | Delete stream link | [View](../operations/deleteWebhooksStreamLink.md) |
| GET | `/2/users/compliance/stream` | Stream Users compliance data | [View](../operations/streamUsersCompliance.md) |
