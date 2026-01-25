# issuing_personalization_design_preferences

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `is_default` | boolean | Yes | Whether we use this personalization design to create cards when one isn't specified. A connected account uses the Connect platform's default design if no personalization design is set as the default design. |
| `is_platform_default` | boolean | No | Whether this personalization design is used to create cards when one is not specified and a default for this connected account does not exist. |

