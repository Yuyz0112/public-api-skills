# Hyperlink

A link to either a URL or another frame (node) in the document.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: URL, NODE | Yes | The type of hyperlink. Can be either `URL` or `NODE`. |
| `url` | string | No | The URL that the hyperlink points to, if `type` is `URL`. |
| `nodeID` | string | No | The ID of the node that the hyperlink points to, if `type` is `NODE`. |

