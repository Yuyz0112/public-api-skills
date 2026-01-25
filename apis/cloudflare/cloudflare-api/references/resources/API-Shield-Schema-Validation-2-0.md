# API Shield Schema Validation 2.0

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| PATCH | `/zones/{zone_id}/api_gateway/operations/schema_validation` | Update multiple operation-level schema validation settings | [View](../operations/api-shield-schema-validation-update-multiple-operation-level-settings.md) |
| GET | `/zones/{zone_id}/api_gateway/operations/{operation_id}/schema_validation` | Retrieve operation-level schema validation settings | [View](../operations/api-shield-schema-validation-retrieve-operation-level-settings.md) |
| PUT | `/zones/{zone_id}/api_gateway/operations/{operation_id}/schema_validation` | Update operation-level schema validation settings | [View](../operations/api-shield-schema-validation-update-operation-level-settings.md) |
| GET | `/zones/{zone_id}/api_gateway/settings/schema_validation` | Retrieve zone level schema validation settings | [View](../operations/api-shield-schema-validation-retrieve-zone-level-settings.md) |
| PUT | `/zones/{zone_id}/api_gateway/settings/schema_validation` | Update zone level schema validation settings | [View](../operations/api-shield-schema-validation-update-zone-level-settings.md) |
| PATCH | `/zones/{zone_id}/api_gateway/settings/schema_validation` | Update zone level schema validation settings | [View](../operations/api-shield-schema-validation-patch-zone-level-settings.md) |
| GET | `/zones/{zone_id}/api_gateway/user_schemas` | Retrieve information about all schemas on a zone | [View](../operations/api-shield-schema-validation-retrieve-information-about-all-schemas.md) |
| POST | `/zones/{zone_id}/api_gateway/user_schemas` | Upload a schema to a zone | [View](../operations/api-shield-schema-validation-post-schema.md) |
| GET | `/zones/{zone_id}/api_gateway/user_schemas/hosts` | Retrieve schema hosts in a zone | [View](../operations/api-shield-schema-validation-retrieve-user-schema-hosts.md) |
| GET | `/zones/{zone_id}/api_gateway/user_schemas/{schema_id}` | Retrieve information about a specific schema on a zone | [View](../operations/api-shield-schema-validation-retrieve-information-about-specific-schema.md) |
| DELETE | `/zones/{zone_id}/api_gateway/user_schemas/{schema_id}` | Delete a schema | [View](../operations/api-shield-schema-delete-a-schema.md) |
| PATCH | `/zones/{zone_id}/api_gateway/user_schemas/{schema_id}` | Enable validation for a schema | [View](../operations/api-shield-schema-validation-enable-validation-for-a-schema.md) |
| GET | `/zones/{zone_id}/api_gateway/user_schemas/{schema_id}/operations` | Retrieve all operations from a schema. | [View](../operations/api-shield-schema-validation-extract-operations-from-schema.md) |
