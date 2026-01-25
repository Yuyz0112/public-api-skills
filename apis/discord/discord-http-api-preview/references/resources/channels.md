# channels

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/channels/{channel_id}` |  | [View](../operations/get-channel.md) |
| DELETE | `/channels/{channel_id}` |  | [View](../operations/delete-channel.md) |
| PATCH | `/channels/{channel_id}` |  | [View](../operations/update-channel.md) |
| POST | `/channels/{channel_id}/followers` |  | [View](../operations/follow-channel.md) |
| GET | `/channels/{channel_id}/invites` |  | [View](../operations/list-channel-invites.md) |
| POST | `/channels/{channel_id}/invites` |  | [View](../operations/create-channel-invite.md) |
| GET | `/channels/{channel_id}/messages` |  | [View](../operations/list-messages.md) |
| POST | `/channels/{channel_id}/messages` |  | [View](../operations/create-message.md) |
| POST | `/channels/{channel_id}/messages/bulk-delete` |  | [View](../operations/bulk-delete-messages.md) |
| GET | `/channels/{channel_id}/messages/pins` |  | [View](../operations/list-pins.md) |
| PUT | `/channels/{channel_id}/messages/pins/{message_id}` |  | [View](../operations/create-pin.md) |
| DELETE | `/channels/{channel_id}/messages/pins/{message_id}` |  | [View](../operations/delete-pin.md) |
| GET | `/channels/{channel_id}/messages/{message_id}` |  | [View](../operations/get-message.md) |
| DELETE | `/channels/{channel_id}/messages/{message_id}` |  | [View](../operations/delete-message.md) |
| PATCH | `/channels/{channel_id}/messages/{message_id}` |  | [View](../operations/update-message.md) |
| POST | `/channels/{channel_id}/messages/{message_id}/crosspost` |  | [View](../operations/crosspost-message.md) |
| DELETE | `/channels/{channel_id}/messages/{message_id}/reactions` |  | [View](../operations/delete-all-message-reactions.md) |
| GET | `/channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}` |  | [View](../operations/list-message-reactions-by-emoji.md) |
| DELETE | `/channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}` |  | [View](../operations/delete-all-message-reactions-by-emoji.md) |
| PUT | `/channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/@me` |  | [View](../operations/add-my-message-reaction.md) |
| DELETE | `/channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/@me` |  | [View](../operations/delete-my-message-reaction.md) |
| DELETE | `/channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/{user_id}` |  | [View](../operations/delete-user-message-reaction.md) |
| POST | `/channels/{channel_id}/messages/{message_id}/threads` |  | [View](../operations/create-thread-from-message.md) |
| PUT | `/channels/{channel_id}/permissions/{overwrite_id}` |  | [View](../operations/set-channel-permission-overwrite.md) |
| DELETE | `/channels/{channel_id}/permissions/{overwrite_id}` |  | [View](../operations/delete-channel-permission-overwrite.md) |
| GET | `/channels/{channel_id}/pins` |  | [View](../operations/deprecated-list-pins.md) |
| PUT | `/channels/{channel_id}/pins/{message_id}` |  | [View](../operations/deprecated-create-pin.md) |
| DELETE | `/channels/{channel_id}/pins/{message_id}` |  | [View](../operations/deprecated-delete-pin.md) |
| GET | `/channels/{channel_id}/polls/{message_id}/answers/{answer_id}` |  | [View](../operations/get-answer-voters.md) |
| POST | `/channels/{channel_id}/polls/{message_id}/expire` |  | [View](../operations/poll-expire.md) |
| PUT | `/channels/{channel_id}/recipients/{user_id}` |  | [View](../operations/add-group-dm-user.md) |
| DELETE | `/channels/{channel_id}/recipients/{user_id}` |  | [View](../operations/delete-group-dm-user.md) |
| POST | `/channels/{channel_id}/send-soundboard-sound` |  | [View](../operations/send-soundboard-sound.md) |
| GET | `/channels/{channel_id}/thread-members` |  | [View](../operations/list-thread-members.md) |
| PUT | `/channels/{channel_id}/thread-members/@me` |  | [View](../operations/join-thread.md) |
| DELETE | `/channels/{channel_id}/thread-members/@me` |  | [View](../operations/leave-thread.md) |
| GET | `/channels/{channel_id}/thread-members/{user_id}` |  | [View](../operations/get-thread-member.md) |
| PUT | `/channels/{channel_id}/thread-members/{user_id}` |  | [View](../operations/add-thread-member.md) |
| DELETE | `/channels/{channel_id}/thread-members/{user_id}` |  | [View](../operations/delete-thread-member.md) |
| POST | `/channels/{channel_id}/threads` |  | [View](../operations/create-thread.md) |
| GET | `/channels/{channel_id}/threads/archived/private` |  | [View](../operations/list-private-archived-threads.md) |
| GET | `/channels/{channel_id}/threads/archived/public` |  | [View](../operations/list-public-archived-threads.md) |
| GET | `/channels/{channel_id}/threads/search` |  | [View](../operations/thread-search.md) |
| POST | `/channels/{channel_id}/typing` |  | [View](../operations/trigger-typing-indicator.md) |
| GET | `/channels/{channel_id}/users/@me/threads/archived/private` |  | [View](../operations/list-my-private-archived-threads.md) |
| GET | `/channels/{channel_id}/webhooks` |  | [View](../operations/list-channel-webhooks.md) |
| POST | `/channels/{channel_id}/webhooks` |  | [View](../operations/create-webhook.md) |
