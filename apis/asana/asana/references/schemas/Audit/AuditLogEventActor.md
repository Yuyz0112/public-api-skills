# AuditLogEventActor

The entity that triggered the event. Will typically be a user.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actor_type` | enum: user, asana, asana_support... | No | The type of actor.
Can be one of `user`, `asana`, `asana_support`, `anonymous`, or `external_administrator`. |
| `gid` | string | No | Globally unique identifier of the actor, if it is a user. |
| `name` | string | No | The name of the actor, if it is a user. |
| `email` | string | No | The email of the actor, if it is a user. |

