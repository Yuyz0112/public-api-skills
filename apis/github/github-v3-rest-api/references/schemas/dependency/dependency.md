# dependency

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `package_url` | string | No | Package-url (PURL) of dependency. See https://github.com/package-url/purl-spec for more details. |
| `metadata` | [metadata](metadata.md) | No |  |
| `relationship` | enum: direct, indirect | No | A notation of whether a dependency is requested directly by this manifest or is a dependency of another dependency. |
| `scope` | enum: runtime, development | No | A notation of whether the dependency is required for the primary build artifact (runtime) or is only used for development. Future versions of this specification may allow for more granular scopes. |
| `dependencies` | string[] | No | Array of package-url (PURLs) of direct child dependencies. |

