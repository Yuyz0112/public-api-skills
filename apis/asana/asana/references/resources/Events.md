# Events

An event is an object representing a change to a resource that was observed by an event subscription. Event streams rely on the same infrastructure as webhooks, which ensures events are delivered within a minute (on average). This system is designed for at most once delivery, meaning in exceptional circumstances a small number of events may be missing from the stream. For this reason, if your use case requires strong guarantees about processing all changes on a resource and cannot tolerate any missing events, regardless of how rare that might be, we recommend building a fallback polling system that fetches the resource periodically as well. Note that while webhooks cannot be replayed once delivered, events are retrievable from the event stream for 24 hours after being processed.

In general, requesting events on a resource is faster and subject to higher rate limits than requesting the resource itself. Additionally, change events "bubble up" (e.g., listening to events on a project would include when stories are added to tasks in the project, and even to subtasks).

Establish an initial sync token by making a request with no sync token. The response will be a `412 Precondition Failed` error - the same as if the sync token had expired.

Subsequent requests should always provide the sync token from the immediately preceding call.

Sync tokens may not be valid if you attempt to go "backward" in the history by requesting previous tokens, though re-requesting the current sync token is generally safe, and will always return the same results.

When you receive a `412 Precondition Failed` error, it means that the sync token is either invalid or expired. If you are attempting to keep a set of data in sync, this signals you may need to re-crawl the data.

Sync tokens always expire after 24 hours, but may expire sooner, depending on load on the service.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/events` | Get events on a resource | [View](../operations/getEvents.md) |
