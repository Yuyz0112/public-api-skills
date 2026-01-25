# Avatars

This resource represents system and custom avatars. Use it to obtain the details of system or custom avatars, add and remove avatars from a project, issue type or priority and obtain avatar images.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/avatar/{type}/system` | Get system avatars by type | [View](../operations/getAllSystemAvatars.md) |
| GET | `/rest/api/3/universal_avatar/type/{type}/owner/{entityId}` | Get avatars | [View](../operations/getAvatars.md) |
| POST | `/rest/api/3/universal_avatar/type/{type}/owner/{entityId}` | Load avatar | [View](../operations/storeAvatar.md) |
| DELETE | `/rest/api/3/universal_avatar/type/{type}/owner/{owningObjectId}/avatar/{id}` | Delete avatar | [View](../operations/deleteAvatar.md) |
| GET | `/rest/api/3/universal_avatar/view/type/{type}` | Get avatar image by type | [View](../operations/getAvatarImageByType.md) |
| GET | `/rest/api/3/universal_avatar/view/type/{type}/avatar/{id}` | Get avatar image by ID | [View](../operations/getAvatarImageByID.md) |
| GET | `/rest/api/3/universal_avatar/view/type/{type}/owner/{entityId}` | Get avatar image by owner | [View](../operations/getAvatarImageByOwner.md) |
