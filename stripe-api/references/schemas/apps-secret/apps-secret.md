# apps.secret

Secret Store is an API that allows Stripe Apps developers to securely persist secrets for use by UI Extensions and app backends.

The primary resource in Secret Store is a `secret`. Other apps can't view secrets created by an app. Additionally, secrets are scoped to provide further permission control.

All Dashboard users and the app backend share `account` scoped secrets. Use the `account` scope for secrets that don't change per-user, like a third-party API key.

A `user` scoped secret is accessible by the app backend and one specific Dashboard user. Use the `user` scope for per-user secrets like per-user OAuth tokens, where different users might have different permissions.

Related guide: [Store data between page reloads](https://docs.stripe.com/stripe-apps/store-auth-data-custom-objects)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `deleted` | boolean | No | If true, indicates that this secret has been deleted |
| `expires_at` | integer (unix-time) | No | The Unix timestamp for the expiry time of the secret, after which the secret deletes. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `name` | string | Yes | A name for the secret that's unique within the scope. |
| `object` | enum: apps.secret | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payload` | string | No | The plaintext secret value to be stored. |
| `scope` | [secret_service_resource_scope](secret-service-resource-scope.md) | Yes |  |

