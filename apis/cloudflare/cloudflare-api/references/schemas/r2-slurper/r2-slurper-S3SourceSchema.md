# r2-slurper_S3SourceSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | Yes |  |
| `endpoint` | string | No |  |
| `pathPrefix` | string | No |  |
| `region` | string | No |  |
| `secret` | [r2-slurper_S3LikeCredsSchema](r2-slurper-S3LikeCredsSchema.md) | Yes |  |
| `vendor` | enum: s3 | Yes |  |

