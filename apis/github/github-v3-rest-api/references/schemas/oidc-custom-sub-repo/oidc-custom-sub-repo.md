# oidc-custom-sub-repo

Actions OIDC subject customization for a repository

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `use_default` | boolean | Yes | Whether to use the default template or not. If `true`, the `include_claim_keys` field is ignored. |
| `include_claim_keys` | string[] | No | Array of unique strings. Each claim key can only contain alphanumeric characters and underscores. |

