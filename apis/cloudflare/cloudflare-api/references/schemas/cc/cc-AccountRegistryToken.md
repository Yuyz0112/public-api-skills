# cc_AccountRegistryToken

Credentials that can be used to interact with the requested image registry.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | [cc_AccountID](cc-AccountID.md) | Yes |  |
| `password` | string | No | The password to use when authenticating to the image registry. |
| `registry_host` | string | Yes | The domain of the image registry the credentials are for. |
| `username` | string | Yes | The username to use when authenticating to the image registry. |

