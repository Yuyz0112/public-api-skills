# POST /2/media/metadata

**Resource:** [Media](../resources/Media.md)
**Create Media metadata**
**Operation ID:** `createMediaMetadata`

Creates metadata for a Media file.

## Request Body

**Content Types:** `application/json`

**Schema:** [MetadataCreateRequest](../schemas/Metadata/MetadataCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[MetadataCreateResponse](../schemas/Metadata/MetadataCreateResponse.md)

## Security

- **OAuth2UserToken**: media.write
- **UserToken**
