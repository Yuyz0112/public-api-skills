# APIEntitiesEvent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `project_id` | integer | No |  |
| `action_name` | string | No |  |
| `target_id` | integer | No |  |
| `target_iid` | integer | No |  |
| `target_type` | string | No |  |
| `author_id` | integer | No |  |
| `target_title` | string | No |  |
| `created_at` | string | No |  |
| `note` | [APIEntitiesNote](APIEntitiesNote.md) | No |  |
| `author` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `wiki_page` | [APIEntitiesWikiPageBasic](APIEntitiesWikiPageBasic.md) | No |  |
| `imported` | Boolean | No |  |
| `imported_from` | string | No |  |
| `push_data` | [APIEntitiesPushEventPayload](APIEntitiesPushEventPayload.md) | No |  |
| `author_username` | string | No |  |

