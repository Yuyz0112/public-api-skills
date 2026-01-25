# PUT /v1/dev_resources

**Resource:** [Dev Resources](../resources/Dev-Resources.md)
**Update dev resources**
**Operation ID:** `putDevResources`

Bulk update dev resources across multiple files.

Ids for dev resources that are successfully updated will show up in the `links_updated` array in the response.

If there are any dev resources that cannot be updated, you may still get a 200 response. These resources will show up in the `errors` array.

## Request Body

A list of dev resources that you want to update.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_dev_resources:write
