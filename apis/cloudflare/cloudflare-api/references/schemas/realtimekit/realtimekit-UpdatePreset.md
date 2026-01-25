# realtimekit_UpdatePreset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | object | No |  |
| `name` | string | No | Name of the preset |
| `permissions` | object | No |  |
| `ui` | object | No |  |

## Nested Fields

### `config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `max_screenshare_count` | integer | No | Maximum number of screen shares that can be active at a given time |
| `max_video_streams` | object | No | Maximum number of streams that are visible on a device |
| `media` | object | No | Media configuration options. eg: Video quality |
| `view_type` | enum: GROUP_CALL, WEBINAR, AUDIO_ROOM | No | Type of the meeting |

#### `config.max_video_streams`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `desktop` | integer | No | Maximum number of video streams visible on desktop devices |
| `mobile` | integer | No | Maximum number of streams visible on mobile devices |

#### `config.media`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `screenshare` | object | No | Configuration options for participant screen shares |
| `video` | object | No | Configuration options for participant videos |

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accept_waiting_requests` | boolean | No | Whether this participant can accept waiting requests |
| `can_accept_production_requests` | boolean | No |  |
| `can_change_participant_permissions` | boolean | No |  |
| `can_edit_display_name` | boolean | No |  |
| `can_livestream` | boolean | No |  |
| `can_record` | boolean | No |  |
| `can_spotlight` | boolean | No |  |
| `chat` | object | No | Chat permissions |
| `connected_meetings` | object | No |  |
| `disable_participant_audio` | boolean | No |  |
| `disable_participant_screensharing` | boolean | No |  |
| `disable_participant_video` | boolean | No |  |
| `hidden_participant` | boolean | No | Whether this participant is visible to others or not |
| `is_recorder` | boolean | No |  |
| `kick_participant` | boolean | No |  |
| `media` | object | No | Media permissions |
| `pin_participant` | boolean | No |  |
| `plugins` | object | No | Plugin permissions |
| `polls` | object | No | Poll permissions |
| `recorder_type` | enum: RECORDER, LIVESTREAMER, NONE | No | Type of the recording peer |
| `show_participant_list` | boolean | No |  |
| `waiting_room_type` | enum: SKIP, ON_PRIVILEGED_USER_ENTRY, SKIP_ON_ACCEPT | No | Waiting room type |

#### `permissions.chat`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `private` | object | No |  |
| `public` | object | No |  |

#### `permissions.connected_meetings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_alter_connected_meetings` | boolean | No |  |
| `can_switch_connected_meetings` | boolean | No |  |
| `can_switch_to_parent_meeting` | boolean | No |  |

#### `permissions.media`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `audio` | object | No | Audio permissions |
| `screenshare` | object | No | Screenshare permissions |
| `video` | object | No | Video permissions |

#### `permissions.plugins`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_close` | boolean | No | Can close plugins that are already open |
| `can_edit_config` | boolean | No | Can edit plugin config |
| `can_start` | boolean | No | Can start plugins |
| `config` | any | No |  |

#### `permissions.polls`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_create` | boolean | No | Can create polls |
| `can_view` | boolean | No | Can view polls |
| `can_vote` | boolean | No | Can vote on polls |

### `ui`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config_diff` | object | No |  |
| `design_tokens` | object | No |  |

#### `ui.design_tokens`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `border_radius` | enum: rounded | No |  |
| `border_width` | enum: thin | No |  |
| `colors` | object | No |  |
| `logo` | string | No |  |
| `spacing_base` | number | No |  |
| `theme` | enum: dark | No |  |

