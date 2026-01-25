# ProjectFeature

Details of a project feature.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `feature` | string | No | The key of the feature. |
| `imageUri` | string | No | URI for the image representing the feature. |
| `localisedDescription` | string | No | Localized display description for the feature. |
| `localisedName` | string | No | Localized display name for the feature. |
| `prerequisites` | string[] | No | List of keys of the features required to enable the feature. |
| `projectId` | integer (int64) | No | The ID of the project. |
| `state` | enum: ENABLED, DISABLED, COMING_SOON | No | The state of the feature. When updating the state of a feature, only ENABLED and DISABLED are supported. Responses can contain all values |
| `toggleLocked` | boolean | No | Whether the state of the feature can be updated. |

