# org-private-registry-configuration

Private registry configuration for an organization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the private registry configuration. |
| `registry_type` | enum: maven_repository, nuget_feed, goproxy_server... | Yes | The registry type. |
| `url` | string (uri) | No | The URL of the private registry. |
| `username` | string | No | The username to use when authenticating with the private registry. |
| `replaces_base` | boolean | No | Whether this private registry replaces the base registry (e.g., npmjs.org for npm, rubygems.org for rubygems). When `true`, Dependabot will only use this registry and will not fall back to the public registry. When `false` (default), Dependabot will use this registry for scoped packages but may fall back to the public registry for other packages. |
| `visibility` | enum: all, private, selected | Yes | Which type of organization repositories have access to the private registry. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |

