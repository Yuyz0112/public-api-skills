# Schema Validation

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/zones/{zone_id}/schema_validation/schemas` | List all uploaded schemas | [View](../operations/schema-validation-list-schemas-paginated.md) |
| POST | `/zones/{zone_id}/schema_validation/schemas` | Upload a schema | [View](../operations/schema-validation-create-schema.md) |
| GET | `/zones/{zone_id}/schema_validation/schemas/hosts` | List hosts covered by uploaded schemas | [View](../operations/schema-validation-list-schema-hosts.md) |
| GET | `/zones/{zone_id}/schema_validation/schemas/{schema_id}` | Get details of a schema | [View](../operations/schema-validation-get-schema.md) |
| DELETE | `/zones/{zone_id}/schema_validation/schemas/{schema_id}` | Delete a schema | [View](../operations/schema-validation-delete-schema.md) |
| PATCH | `/zones/{zone_id}/schema_validation/schemas/{schema_id}` | Edit details of a schema to enable validation | [View](../operations/schema-validation-edit-schema.md) |
| GET | `/zones/{zone_id}/schema_validation/schemas/{schema_id}/operations` | Retrieve all operations from the schema. | [View](../operations/schema-validation-extract-operations-from-schema.md) |
