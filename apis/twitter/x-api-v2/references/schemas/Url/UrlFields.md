# UrlFields

Represent the portion of text recognized as a URL.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | Description of the URL landing page. |
| `display_url` | string | No | The URL as displayed in the X client. |
| `expanded_url` | [Url](Url.md) | No |  |
| `images` | UrlImage[] | No |  |
| `media_key` | [MediaKey](MediaKey.md) | No |  |
| `status` | [HttpStatusCode](HttpStatusCode.md) | No |  |
| `title` | string | No | Title of the page the URL points to. |
| `unwound_url` | string (uri) | No | Fully resolved url. |
| `url` | [Url](Url.md) | Yes |  |

