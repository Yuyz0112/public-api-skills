# PUT /rest/atlassian-connect/1/migration/properties/{entityType}

**Resource:** [App migration](../resources/App-migration.md)
**Bulk update entity properties**
**Operation ID:** `MigrationResource.updateEntityPropertiesValue_put`

Updates the values of multiple entity properties for an object, up to 50 updates per request. This operation is for use by Connect apps during app migration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Atlassian-Transfer-Id` | header | string (uuid) | Yes | The app migration transfer ID. |
| `entityType` | path | enum: IssueProperty, CommentProperty, DashboardItemProperty... | Yes | The type indicating the object that contains the entity properties. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [EntityPropertyDetails](../schemas/Entity/EntityPropertyDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 403 | Returned if the authorisation credentials are incorrect or missing. |

