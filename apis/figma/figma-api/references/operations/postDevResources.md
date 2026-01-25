# POST /v1/dev_resources

**Resource:** [Dev Resources](../resources/Dev-Resources.md)
**Create dev resources**
**Operation ID:** `postDevResources`

Bulk create dev resources across multiple files.
Dev resources that are successfully created will show up in the links_created array in the response.

If there are any dev resources that cannot be created, you may still get a 200 response. These resources will show up in the errors array. Some reasons a dev resource cannot be created include:

- Resource points to a `file_key` that cannot be found.
- The node already has the maximum of 10 dev resources.
- Another dev resource for the node has the same url.

## Request Body

A list of dev resources that you want to create.

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
