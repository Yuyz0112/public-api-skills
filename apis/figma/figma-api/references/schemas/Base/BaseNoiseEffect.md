# BaseNoiseEffect

A noise effect

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: NOISE | Yes | The string literal 'NOISE' representing the effect's type. Always check the type before reading other properties. |
| `color` | [RGBA](RGBA.md) | Yes |  |
| `visible` | boolean | Yes | Whether the noise effect is visible. |
| `blendMode` | [BlendMode](BlendMode.md) | Yes |  |
| `noiseSize` | number | Yes | The size of the noise effect |
| `density` | number | Yes | The density of the noise effect |

