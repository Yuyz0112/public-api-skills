# Tags

A Tag is applied to Escalation Policies, Teams or Users and can be used to filter them.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/{entity_type}/{id}/change_tags` | Assign tags | [View](../operations/createEntityTypeByIdChangeTags.md) |
| GET | `/{entity_type}/{id}/tags` | Get tags for entities | [View](../operations/getEntityTypeByIdTags.md) |
| GET | `/tags` | List tags | [View](../operations/listTags.md) |
| POST | `/tags` | Create a tag | [View](../operations/createTags.md) |
| GET | `/tags/{id}` | Get a tag | [View](../operations/getTag.md) |
| DELETE | `/tags/{id}` | Delete a tag | [View](../operations/deleteTag.md) |
| GET | `/tags/{id}/{entity_type}` | Get connected entities | [View](../operations/getTagsByEntityType.md) |
