# actions-hosted-runner-curated-image

Provides details of a hosted runner image

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of the image. Use this ID for the `image` parameter when creating a new larger runner. |
| `platform` | string | Yes | The operating system of the image. |
| `size_gb` | integer | Yes | Image size in GB. |
| `display_name` | string | Yes | Display name for this image. |
| `source` | enum: github, partner, custom | Yes | The image provider. |

