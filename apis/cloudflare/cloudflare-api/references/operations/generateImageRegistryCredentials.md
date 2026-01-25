# POST /accounts/{account_id}/containers/registries/{domain}/credentials

**Resource:** [Image Registries](../resources/Image-Registries.md)
**Generate a JWT to interact with the specified image registry.**
**Operation ID:** `generateImageRegistryCredentials`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cc_ImageRegistryCredentialsConfiguration](../schemas/cc/cc-ImageRegistryCredentialsConfiguration.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | (reference) |
| 400 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
