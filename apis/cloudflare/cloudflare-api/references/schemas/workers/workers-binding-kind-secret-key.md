# workers_binding_kind_secret_key

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `algorithm` | object | Yes | Algorithm-specific key parameters. [Learn more](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/importKey#algorithm). |
| `format` | enum: raw, pkcs8, spki... | Yes | Data format of the key. [Learn more](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/importKey#format). |
| `key_base64` | string | No | Base64-encoded key data. Required if `format` is "raw", "pkcs8", or "spki". |
| `key_jwk` | object | No | Key data in [JSON Web Key](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/importKey#json_web_key) format. Required if `format` is "jwk". |
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `type` | enum: secret_key | Yes | The kind of resource that the binding provides. |
| `usages` | string[] | Yes | Allowed operations with the key. [Learn more](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/importKey#keyUsages). |

