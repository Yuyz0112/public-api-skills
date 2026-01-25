# actions-hosted-runner-custom-image

Provides details of a custom runner image

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the image. Use this ID for the `image` parameter when creating a new larger runner. |
| `platform` | string | Yes | The operating system of the image. |
| `total_versions_size` | integer | Yes | Total size of all the image versions in GB. |
| `name` | string | Yes | Display name for this image. |
| `source` | string | Yes | The image provider. |
| `versions_count` | integer | Yes | The number of image versions associated with the image. |
| `latest_version` | string | Yes | The latest image version associated with the image. |
| `state` | string | Yes | The number of image versions associated with the image. |

