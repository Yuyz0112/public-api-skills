# realtimekit_Preset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | object | Yes |  |
| `name` | string | Yes | Name of the preset |
| `permissions` | object | No |  |
| `ui` | object | Yes |  |

## Nested Fields

### `config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `max_screenshare_count` | integer | Yes | Maximum number of screen shares that can be active at a given time |
| `max_video_streams` | object | Yes | Maximum number of streams that are visible on a device |
| `media` | object | Yes | Media configuration options. eg: Video quality |
| `view_type` | enum: GROUP_CALL, WEBINAR, AUDIO_ROOM | Yes | Type of the meeting |

#### `config.max_video_streams`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `desktop` | integer | Yes | Maximum number of video streams visible on desktop devices |
| `mobile` | integer | Yes | Maximum number of streams visible on mobile devices |

#### `config.media`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `audio` | object | No | Control options for Audio quality. |
| `screenshare` | object | Yes | Configuration options for participant screen shares |
| `video` | object | Yes | Configuration options for participant videos |

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accept_waiting_requests` | boolean | Yes | Whether this participant can accept waiting requests |
| `can_accept_production_requests` | boolean | Yes |  |
| `can_change_participant_permissions` | boolean | Yes |  |
| `can_edit_display_name` | boolean | Yes |  |
| `can_livestream` | boolean | Yes |  |
| `can_record` | boolean | Yes |  |
| `can_spotlight` | boolean | Yes |  |
| `chat` | object | Yes | Chat permissions |
| `connected_meetings` | object | Yes |  |
| `disable_participant_audio` | boolean | Yes |  |
| `disable_participant_screensharing` | boolean | Yes |  |
| `disable_participant_video` | boolean | Yes |  |
| `hidden_participant` | boolean | Yes | Whether this participant is visible to others or not |
| `is_recorder` | boolean | No |  |
| `kick_participant` | boolean | Yes |  |
| `media` | object | Yes | Media permissions |
| `pin_participant` | boolean | Yes |  |
| `plugins` | object | Yes | Plugin permissions |
| `polls` | object | Yes | Poll permissions |
| `recorder_type` | enum: RECORDER, LIVESTREAMER, NONE | Yes | Type of the recording peer |
| `show_participant_list` | boolean | Yes |  |
| `waiting_room_type` | enum: SKIP, ON_PRIVILEGED_USER_ENTRY, SKIP_ON_ACCEPT | Yes | Waiting room type |

#### `permissions.chat`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `private` | object | Yes |  |
| `public` | object | Yes |  |

#### `permissions.connected_meetings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_alter_connected_meetings` | boolean | Yes |  |
| `can_switch_connected_meetings` | boolean | Yes |  |
| `can_switch_to_parent_meeting` | boolean | Yes |  |

#### `permissions.media`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `audio` | object | Yes | Audio permissions |
| `screenshare` | object | Yes | Screenshare permissions |
| `video` | object | Yes | Video permissions |

#### `permissions.plugins`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_close` | boolean | Yes | Can close plugins that are already open |
| `can_edit_config` | boolean | Yes | Can edit plugin config |
| `can_start` | boolean | Yes | Can start plugins |
| `config` | any | Yes |  |

#### `permissions.polls`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_create` | boolean | Yes | Can create polls |
| `can_view` | boolean | Yes | Can view polls |
| `can_vote` | boolean | Yes | Can vote on polls |

### `ui`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config_diff` | object | No |  |
| `design_tokens` | object | Yes |  |

#### `ui.design_tokens`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `border_radius` | enum: rounded | Yes |  |
| `border_width` | enum: thin | Yes |  |
| `colors` | object | Yes |  |
| `logo` | string | Yes |  |
| `spacing_base` | number | Yes |  |
| `theme` | enum: dark | Yes |  |

