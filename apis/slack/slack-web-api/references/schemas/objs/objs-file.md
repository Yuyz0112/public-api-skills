# objs_file

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `channels` | defs_channel_id[] | No |  |
| `comments_count` | integer | No |  |
| `created` | integer | No |  |
| `date_delete` | integer | No |  |
| `display_as_bot` | boolean | No |  |
| `editable` | boolean | No |  |
| `editor` | [defs_user_id](defs-user-id.md) | No |  |
| `external_id` | string | No |  |
| `external_type` | string | No |  |
| `external_url` | string (uri) | No |  |
| `filetype` | string | No |  |
| `groups` | defs_group_id[] | No |  |
| `has_rich_preview` | boolean | No |  |
| `id` | [defs_file_id](defs-file-id.md) | No |  |
| `image_exif_rotation` | integer | No |  |
| `ims` | defs_dm_id[] | No |  |
| `is_external` | boolean | No |  |
| `is_public` | boolean | No |  |
| `is_starred` | boolean | No |  |
| `is_tombstoned` | boolean | No |  |
| `last_editor` | [defs_user_id](defs-user-id.md) | No |  |
| `mimetype` | string | No |  |
| `mode` | string | No |  |
| `name` | string | No |  |
| `non_owner_editable` | boolean | No |  |
| `num_stars` | integer | No |  |
| `original_h` | integer | No |  |
| `original_w` | integer | No |  |
| `permalink` | string (uri) | No |  |
| `permalink_public` | string (uri) | No |  |
| `pinned_info` | [defs_pinned_info](defs-pinned-info.md) | No |  |
| `pinned_to` | defs_channel[] | No |  |
| `pretty_type` | string | No |  |
| `preview` | string | No |  |
| `public_url_shared` | boolean | No |  |
| `reactions` | objs_reaction[] | No |  |
| `shares` | object | No |  |
| `size` | integer | No |  |
| `source_team` | [defs_team](defs-team.md) | No |  |
| `state` | string | No |  |
| `thumb_1024` | string (uri) | No |  |
| `thumb_1024_h` | integer | No |  |
| `thumb_1024_w` | integer | No |  |
| `thumb_160` | string (uri) | No |  |
| `thumb_360` | string (uri) | No |  |
| `thumb_360_h` | integer | No |  |
| `thumb_360_w` | integer | No |  |
| `thumb_480` | string (uri) | No |  |
| `thumb_480_h` | integer | No |  |
| `thumb_480_w` | integer | No |  |
| `thumb_64` | string (uri) | No |  |
| `thumb_720` | string (uri) | No |  |
| `thumb_720_h` | integer | No |  |
| `thumb_720_w` | integer | No |  |
| `thumb_80` | string (uri) | No |  |
| `thumb_800` | string (uri) | No |  |
| `thumb_800_h` | integer | No |  |
| `thumb_800_w` | integer | No |  |
| `thumb_960` | string (uri) | No |  |
| `thumb_960_h` | integer | No |  |
| `thumb_960_w` | integer | No |  |
| `thumb_tiny` | string | No |  |
| `timestamp` | integer | No |  |
| `title` | string | No |  |
| `updated` | integer | No |  |
| `url_private` | string (uri) | No |  |
| `url_private_download` | string (uri) | No |  |
| `user` | string | No |  |
| `user_team` | [defs_team](defs-team.md) | No |  |
| `username` | string | No |  |

## Nested Fields

### `shares`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `private` | any | No |  |
| `public` | any | No |  |

