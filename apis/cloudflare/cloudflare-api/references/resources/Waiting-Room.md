# Waiting Room

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/waiting_rooms` | List waiting rooms for account | [View](../operations/waiting-room-list-waiting-rooms-account.md) |
| GET | `/zones/{zone_id}/waiting_rooms` | List waiting rooms for zone | [View](../operations/waiting-room-list-waiting-rooms.md) |
| POST | `/zones/{zone_id}/waiting_rooms` | Create waiting room | [View](../operations/waiting-room-create-waiting-room.md) |
| POST | `/zones/{zone_id}/waiting_rooms/preview` | Create a custom waiting room page preview | [View](../operations/waiting-room-create-a-custom-waiting-room-page-preview.md) |
| GET | `/zones/{zone_id}/waiting_rooms/settings` | Get zone-level Waiting Room settings | [View](../operations/waiting-room-get-zone-settings.md) |
| PUT | `/zones/{zone_id}/waiting_rooms/settings` | Update zone-level Waiting Room settings | [View](../operations/waiting-room-update-zone-settings.md) |
| PATCH | `/zones/{zone_id}/waiting_rooms/settings` | Patch zone-level Waiting Room settings | [View](../operations/waiting-room-patch-zone-settings.md) |
| GET | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}` | Waiting room details | [View](../operations/waiting-room-waiting-room-details.md) |
| PUT | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}` | Update waiting room | [View](../operations/waiting-room-update-waiting-room.md) |
| DELETE | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}` | Delete waiting room | [View](../operations/waiting-room-delete-waiting-room.md) |
| PATCH | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}` | Patch waiting room | [View](../operations/waiting-room-patch-waiting-room.md) |
| GET | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/events` | List events | [View](../operations/waiting-room-list-events.md) |
| POST | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/events` | Create event | [View](../operations/waiting-room-create-event.md) |
| GET | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}` | Event details | [View](../operations/waiting-room-event-details.md) |
| PUT | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}` | Update event | [View](../operations/waiting-room-update-event.md) |
| DELETE | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}` | Delete event | [View](../operations/waiting-room-delete-event.md) |
| PATCH | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}` | Patch event | [View](../operations/waiting-room-patch-event.md) |
| GET | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}/details` | Preview active event details | [View](../operations/waiting-room-preview-active-event-details.md) |
| GET | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules` | List Waiting Room Rules | [View](../operations/waiting-room-list-waiting-room-rules.md) |
| PUT | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules` | Replace Waiting Room Rules | [View](../operations/waiting-room-replace-waiting-room-rules.md) |
| POST | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules` | Create Waiting Room Rule | [View](../operations/waiting-room-create-waiting-room-rule.md) |
| DELETE | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules/{rule_id}` | Delete Waiting Room Rule | [View](../operations/waiting-room-delete-waiting-room-rule.md) |
| PATCH | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules/{rule_id}` | Patch Waiting Room Rule | [View](../operations/waiting-room-patch-waiting-room-rule.md) |
| GET | `/zones/{zone_id}/waiting_rooms/{waiting_room_id}/status` | Get waiting room status | [View](../operations/waiting-room-get-waiting-room-status.md) |
