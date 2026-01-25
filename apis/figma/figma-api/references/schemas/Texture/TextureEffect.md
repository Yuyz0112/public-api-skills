# TextureEffect

A texture effect

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: TEXTURE | Yes | The string literal 'TEXTURE' representing the effect's type. Always check the type before reading other properties. |
| `visible` | boolean | Yes | Whether the texture effect is visible. |
| `noiseSize` | number | Yes | The size of the texture effect |
| `radius` | number | Yes | The radius of the texture effect |
| `clipToShape` | boolean | Yes | Whether the texture is clipped to the shape |

