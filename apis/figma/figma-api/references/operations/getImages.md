# GET /v1/images/{file_key}

**Resource:** [Files](../resources/Files.md)
**Render images of file nodes**
**Operation ID:** `getImages`

Renders images from a file.

If no error occurs, `"images"` will be populated with a map from node IDs to URLs of the rendered images, and `"status"` will be omitted. The image assets will expire after 30 days. Images up to 32 megapixels can be exported. Any images that are larger will be scaled down.

Important: the image map may contain values that are `null`. This indicates that rendering of that specific node has failed. This may be due to the node id not existing, or other reasons such has the node having no renderable components. It is guaranteed that any node that was requested for rendering will be represented in this map whether or not the render succeeded.

To render multiple images from the same file, use the `ids` query parameter to specify multiple node ids.

```
GET /v1/images/:key?ids=1:2,1:3,1:4
```


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to export images from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `ids` | query | string | Yes | A comma separated list of node IDs to render. |
| `version` | query | string | No | A specific version ID to get. Omitting this will get the current version of the file. |
| `scale` | query | number | No | A number between 0.01 and 4, the image scaling factor. |
| `format` | query | enum: jpg, png, svg... | No | A string enum for the image output format. |
| `svg_outline_text` | query | boolean | No | Whether text elements are rendered as outlines (vector paths) or as `<text>` elements in SVGs.

Rendering text elements as outlines guarantees that the text looks exactly the same in the SVG as it does in the browser/inside Figma.

Exporting as `<text>` allows text to be selectable inside SVGs and generally makes the SVG easier to read. However, this relies on the browser's rendering engine which can vary between browsers and/or operating systems. As such, visual accuracy is not guaranteed as the result could look different than in Figma. |
| `svg_include_id` | query | boolean | No | Whether to include id attributes for all SVG elements. Adds the layer name to the `id` attribute of an svg element. |
| `svg_include_node_id` | query | boolean | No | Whether to include node id attributes for all SVG elements. Adds the node id to a `data-node-id` attribute of an svg element. |
| `svg_simplify_stroke` | query | boolean | No | Whether to simplify inside/outside strokes and use stroke attribute if possible instead of `<mask>`. |
| `contents_only` | query | boolean | No | Whether content that overlaps the node should be excluded from rendering. Passing false (i.e., rendering overlaps) may increase processing time, since more of the document must be included in rendering. |
| `use_absolute_bounds` | query | boolean | No | Use the full dimensions of the node regardless of whether or not it is cropped or the space around it is empty. Use this to export text nodes without cropping. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_content:read, files:read
