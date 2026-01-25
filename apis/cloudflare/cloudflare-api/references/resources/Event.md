# Event

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/cloudforce-one/events` | Filter and list events | [View](../operations/get-EventListGet.md) |
| GET | `/accounts/{account_id}/cloudforce-one/events/aggregate` | Aggregate events by single or multiple columns with optional date filtering | [View](../operations/get-EventAggregate.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/create` | Creates a new event | [View](../operations/post-EventCreate.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/create/bulk` | Creates bulk events | [View](../operations/post-EventCreateBulk.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/create/bulk/relationships` | Creates bulk DOS event with relationships and indicators | [View](../operations/post-DOSEventCreateBulkWithRelationships.md) |
| GET | `/accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/events/{event_id}` | Reads an event | [View](../operations/get-EventRead.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/move` | Moves specified events from one dataset to another dataset | [View](../operations/post-EventMoveToNewDS.md) |
| DELETE | `/accounts/{account_id}/cloudforce-one/events/event_tag/{event_id}` | Removes a tag from an event | [View](../operations/delete-EventTagDelete.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/event_tag/{event_id}/create` | Adds a tag to an event | [View](../operations/post-EventTagCreate.md) |
| GET | `/accounts/{account_id}/cloudforce-one/events/raw/{dataset_id}/{event_id}` | Reads data for a raw event | [View](../operations/get-EventRawReadDS.md) |
| DELETE | `/accounts/{account_id}/cloudforce-one/events/relate/{event_id}` | Removes an event reference | [View](../operations/delete-EventReferenceDelete.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/relate/{event_id}/create` | Creates event references for a event | [View](../operations/post-EventReferenceCreate.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/relationships/create` | Create a relationship between two events | [View](../operations/post-CreateEventRelationship.md) |
| DELETE | `/accounts/{account_id}/cloudforce-one/events/{dataset_id}/delete` | Deletes one or more events | [View](../operations/delete-EventDeleteDO.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/{dataset_id}/revert-do` | Revert an Events Durable Object to a point in time | [View](../operations/post-EventDoRevert.md) |
| GET | `/accounts/{account_id}/cloudforce-one/events/{event_id}` | Reads an event | [View](../operations/get-EventReadDeprecated.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/{event_id}` | Updates an event | [View](../operations/post-EventUpdate.md) |
| DELETE | `/accounts/{account_id}/cloudforce-one/events/{event_id}` | Deletes an event | [View](../operations/delete-EventDelete.md) |
| PATCH | `/accounts/{account_id}/cloudforce-one/events/{event_id}` | Updates an event | [View](../operations/patch-EventUpdate.md) |
| GET | `/accounts/{account_id}/cloudforce-one/events/{event_id}/raw/{raw_id}` | Reads data for a raw event | [View](../operations/get-EventRawRead.md) |
| POST | `/accounts/{account_id}/cloudforce-one/events/{event_id}/raw/{raw_id}` | Updates a raw event | [View](../operations/post-EventRawUpdate.md) |
| PATCH | `/accounts/{account_id}/cloudforce-one/events/{event_id}/raw/{raw_id}` | Updates a raw event | [View](../operations/patch-EventRawUpdate.md) |
| GET | `/accounts/{account_id}/cloudforce-one/events/{event_id}/relationships` | Filter and list events related to specific event | [View](../operations/get-EventRelationships.md) |
| POST | `/accounts/{account_id}/cloudforce-one/v2/events/graphql` | GraphQL endpoint for event aggregation | [View](../operations/post-EventGraphQL.md) |
