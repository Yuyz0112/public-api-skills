# r2_enable_sippy_aws

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `destination` | object | No | R2 bucket to copy objects to. |
| `source` | object | No | AWS S3 bucket to copy objects from. |

## Nested Fields

### `destination`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessKeyId` | string | No | ID of a Cloudflare API token.
This is the value labelled "Access Key ID" when creating an API.
token from the [R2 dashboard](https://dash.cloudflare.com/?to=/:account/r2/api-tokens).

Sippy will use this token when writing objects to R2, so it is
best to scope this token to the bucket you're enabling Sippy for.
 |
| `provider` | enum: r2 | No |  |
| `secretAccessKey` | string | No | Value of a Cloudflare API token.
This is the value labelled "Secret Access Key" when creating an API.
token from the [R2 dashboard](https://dash.cloudflare.com/?to=/:account/r2/api-tokens).

Sippy will use this token when writing objects to R2, so it is
best to scope this token to the bucket you're enabling Sippy for.
 |

### `source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessKeyId` | string | No | Access Key ID of an IAM credential (ideally scoped to a single S3 bucket). |
| `bucket` | string | No | Name of the AWS S3 bucket. |
| `provider` | enum: aws | No |  |
| `region` | string | No | Name of the AWS availability zone. |
| `secretAccessKey` | string | No | Secret Access Key of an IAM credential (ideally scoped to a single S3 bucket). |

