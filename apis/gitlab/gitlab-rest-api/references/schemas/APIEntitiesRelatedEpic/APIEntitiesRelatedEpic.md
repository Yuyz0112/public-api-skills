# APIEntitiesRelatedEpic

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `work_item_id` | integer | No |  |
| `iid` | integer | No |  |
| `color` | string | No |  |
| `text_color` | string | No |  |
| `group_id` | integer | No |  |
| `parent_id` | integer | No |  |
| `parent_iid` | integer | No |  |
| `imported` | Boolean | No |  |
| `imported_from` | string | No |  |
| `title` | string | No |  |
| `description` | string | No |  |
| `confidential` | Boolean | No |  |
| `author` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `start_date` | DateTime | No |  |
| `start_date_is_fixed` | Boolean | No |  |
| `start_date_fixed` | DateTime | No |  |
| `start_date_from_inherited_source` | DateTime | No |  |
| `start_date_from_milestones` | DateTime | No |  |
| `end_date` | DateTime | No |  |
| `due_date` | DateTime | No |  |
| `due_date_is_fixed` | Boolean | No |  |
| `due_date_fixed` | DateTime | No |  |
| `due_date_from_inherited_source` | DateTime | No |  |
| `due_date_from_milestones` | DateTime | No |  |
| `state` | string | No |  |
| `web_edit_url` | string | No |  |
| `web_url` | string | No |  |
| `references` | string[] | No |  |
| `reference` | string | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `closed_at` | DateTime | No |  |
| `labels` | string[] | No |  |
| `upvotes` | integer | No |  |
| `downvotes` | integer | No |  |
| `subscribed` | Boolean | No |  |
| `_links` | string | No |  |
| `related_epic_link_id` | string | No |  |
| `link_type` | string | No |  |
| `link_created_at` | string | No |  |
| `link_updated_at` | string | No |  |

