# r2_sippy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `destination` | object | No | Details about the configured destination bucket. |
| `enabled` | boolean | No | State of Sippy for this bucket. |
| `source` | object | No | Details about the configured source bucket. |

## Nested Fields

### `destination`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessKeyId` | string | No | ID of the Cloudflare API token used when writing objects to this
bucket.
 |
| `account` | string | No |  |
| `bucket` | string | No | Name of the bucket on the provider. |
| `provider` | enum: r2 | No |  |

### `source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | No | Name of the bucket on the provider (AWS, GCS only). |
| `bucketUrl` | string | No | S3-compatible URL (Generic S3-compatible providers only). |
| `provider` | enum: aws, gcs, s3 | No |  |
| `region` | string | No | Region where the bucket resides (AWS only). |

