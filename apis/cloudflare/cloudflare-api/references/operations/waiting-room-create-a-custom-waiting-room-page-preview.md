# POST /zones/{zone_id}/waiting_rooms/preview

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Create a custom waiting room page preview**
**Operation ID:** `waiting-room-create-a-custom-waiting-room-page-preview`

Creates a waiting room page preview. Upload a custom waiting room page for preview. You will receive a preview URL in the form `http://waitingrooms.dev/preview/<uuid>`. You can use the following query parameters to change the state of the preview:
1. `force_queue`: Boolean indicating if all users will be queued in the waiting room and no one will be let into the origin website (also known as queueAll).
2. `queue_is_full`: Boolean indicating if the waiting room's queue is currently full and not accepting new users at the moment.
3. `queueing_method`: The queueing method currently used by the waiting room.
	- **fifo** indicates a FIFO queue.
	- **random** indicates a Random queue.
	- **passthrough** indicates a Passthrough queue. Keep in mind that the waiting room page will only be displayed if `force_queue=true` or `event=prequeueing` — for other cases the request will pass through to the origin. For our preview, this will be a fake origin website returning \"Welcome\". 
	- **reject** indicates a Reject queue.
4. `event`: Used to preview a waiting room event.
	- **none** indicates no event is occurring.
	- **prequeueing** indicates that an event is prequeueing (between `prequeue_start_time` and `event_start_time`).
	- **started** indicates that an event has started (between `event_start_time` and `event_end_time`).
5. `shuffle_at_event_start`: Boolean indicating if the event will shuffle users in the prequeue when it starts. This can only be set to **true** if an event is active (`event` is not **none**).

For example, you can make a request to `http://waitingrooms.dev/preview/<uuid>?force_queue=false&queue_is_full=false&queueing_method=random&event=started&shuffle_at_event_start=true`
6. `waitTime`: Non-zero, positive integer indicating the estimated wait time in minutes. The default value is 10 minutes.

For example, you can make a request to `http://waitingrooms.dev/preview/<uuid>?waitTime=50` to configure the estimated wait time as 50 minutes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_query_preview](../schemas/waitingroom/waitingroom-query-preview.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a custom waiting room page preview response |
| 4XX | Create a custom waiting room page preview response failure |

**Success Response Schema:**

[waitingroom_preview_response](../schemas/waitingroom/waitingroom-preview-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
