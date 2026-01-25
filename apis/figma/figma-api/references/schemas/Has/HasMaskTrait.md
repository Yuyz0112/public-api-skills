# HasMaskTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isMask` | boolean | No | Does this node mask sibling nodes in front of it? |
| `maskType` | enum: ALPHA, VECTOR, LUMINANCE | No | If this layer is a mask, this property describes the operation used to mask the layer's siblings. The value may be one of the following:

- ALPHA: the mask node's alpha channel will be used to determine the opacity of each pixel in the masked result.
- VECTOR: if the mask node has visible fill paints, every pixel inside the node's fill regions will be fully visible in the masked result. If the mask has visible stroke paints, every pixel inside the node's stroke regions will be fully visible in the masked result.
- LUMINANCE: the luminance value of each pixel of the mask node will be used to determine the opacity of that pixel in the masked result. |
| `isMaskOutline` | boolean | No | True if maskType is VECTOR. This field is deprecated; use maskType instead. |

