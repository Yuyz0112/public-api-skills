# api-shield_public_schema

A schema used in schema validation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | [api-shield_schemas-timestamp](api-shield-schemas-timestamp.md) | Yes |  |
| `kind` | enum: openapi_v3 | Yes | The kind of the schema |
| `name` | string | Yes | A human-readable name for the schema |
| `schema_id` | string | Yes |  |
| `source` | string | Yes | The raw schema, e.g., the OpenAPI schema, either as JSON or YAML |
| `validation_enabled` | boolean | No | An indicator if this schema is enabled |

