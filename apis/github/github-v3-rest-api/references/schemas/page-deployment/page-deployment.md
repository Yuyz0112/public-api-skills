# page-deployment

The GitHub Pages deployment status.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | any | Yes | The ID of the GitHub Pages deployment. This is the Git SHA of the deployed commit. |
| `status_url` | string (uri) | Yes | The URI to monitor GitHub Pages deployment status. |
| `page_url` | string (uri) | Yes | The URI to the deployed GitHub Pages. |
| `preview_url` | string (uri) | No | The URI to the deployed GitHub Pages preview. |

