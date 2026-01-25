# MetadataCreateResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `associated_metadata` | object | No |  |
| `id` | [MediaId](MediaId.md) | No |  |

#### `data.associated_metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allow_download_status` | [AllowDownloadStatus](AllowDownloadStatus.md) | No |  |
| `alt_text` | [AltText](AltText.md) | No |  |
| `audience_policy` | [AudiencePolicy](AudiencePolicy.md) | No |  |
| `content_expiration` | [ContentExpiration](ContentExpiration.md) | No |  |
| `domain_restrictions` | [DomainRestrictions](DomainRestrictions.md) | No |  |
| `found_media_origin` | [FoundMediaOrigin](FoundMediaOrigin.md) | No |  |
| `geo_restrictions` | [GeoRestrictions](GeoRestrictions.md) | No |  |
| `management_info` | [ManagementInfo](ManagementInfo.md) | No |  |
| `preview_image` | [PreviewImage](PreviewImage.md) | No |  |
| `sensitive_media_warning` | [SensitiveMediaWarning](SensitiveMediaWarning.md) | No |  |
| `shared_info` | [SharedInfo](SharedInfo.md) | No |  |
| `sticker_info` | [StickerInfo](StickerInfo.md) | No |  |
| `upload_source` | [UploadSource](UploadSource.md) | No |  |

