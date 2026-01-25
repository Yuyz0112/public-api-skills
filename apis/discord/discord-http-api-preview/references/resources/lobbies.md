# lobbies

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| PUT | `/lobbies` |  | [View](../operations/create-or-join-lobby.md) |
| POST | `/lobbies` |  | [View](../operations/create-lobby.md) |
| GET | `/lobbies/{lobby_id}` |  | [View](../operations/get-lobby.md) |
| PATCH | `/lobbies/{lobby_id}` |  | [View](../operations/edit-lobby.md) |
| PATCH | `/lobbies/{lobby_id}/channel-linking` |  | [View](../operations/edit-lobby-channel-link.md) |
| DELETE | `/lobbies/{lobby_id}/members/@me` |  | [View](../operations/leave-lobby.md) |
| POST | `/lobbies/{lobby_id}/members/@me/invites` |  | [View](../operations/create-linked-lobby-guild-invite-for-self.md) |
| POST | `/lobbies/{lobby_id}/members/bulk` |  | [View](../operations/bulk-update-lobby-members.md) |
| PUT | `/lobbies/{lobby_id}/members/{user_id}` |  | [View](../operations/add-lobby-member.md) |
| DELETE | `/lobbies/{lobby_id}/members/{user_id}` |  | [View](../operations/delete-lobby-member.md) |
| POST | `/lobbies/{lobby_id}/members/{user_id}/invites` |  | [View](../operations/create-linked-lobby-guild-invite-for-user.md) |
| GET | `/lobbies/{lobby_id}/messages` |  | [View](../operations/get-lobby-messages.md) |
| POST | `/lobbies/{lobby_id}/messages` |  | [View](../operations/create-lobby-message.md) |
