# SingleRedactionRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `contentItem` | [ContentItem](ContentItem.md) | Yes |  |
| `externalId` | string (uuid) | Yes | Unique id for the redaction request; ID format should be of UUID |
| `reason` | string | Yes | The reason why the content is being redacted |
| `redactionPosition` | [RedactionPosition](RedactionPosition.md) | Yes |  |

