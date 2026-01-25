# POST /v1/files/{file_key}/variables

**Resource:** [Variables](../resources/Variables.md)
**Create/modify/delete variables**
**Operation ID:** `postVariables`

**This API is available to full members of Enterprise orgs with Editor seats.**

The `POST /v1/files/:file_key/variables` endpoint lets you bulk create, update, and delete variables and variable collections.

The request body supports the following 4 top-level arrays. Changes from these arrays will be applied in the below order, and within each array, by array order.

- **variableCollections**: For creating, updating, and deleting variable collections
- **variableModes**: For creating, updating, and deleting modes within variable collections
  - Each collection can have a maximum of 40 modes
  - Mode names cannot be longer than 40 characters
- **variables**: For creating, updating, and deleting variables
  - Each collection can have a maximum of 5000 variables
  - Variable names must be unique within a collection and cannot contain certain special characters such as `.{}`
- **variableModeValues**: For setting a variable value under a specific mode.
  - When setting aliases, a variable cannot be aliased to itself or form an alias cycle

Temporary ids can be used to reference an object later in the same POST request body. They can be used at create time in the `id` property of variable collections, modes, variables, and in the `initialModeId` property of variable collections. They are scoped to a single request body, and must be unique within the body. The mapping of temporary ids to real ids is returned in the response.

This endpoint has the following key behaviors:

- The request body must be 4MB or less.
- Must include an `action` property for collections, modes, and variables to tell the API whether to create, update, or delete the object.
- When creating a collection, mode, or variable, you can include a temporary `id` that can be referenced in dependent objects in the same request. For example, you can create a new collection with the id `"my_new_collection"`. You can then set `variableCollectionId` to `"my_new_collection"` in new modes or variables. Temporary ids must be unique in the request body.
- New collections always come with one mode. You can reference this mode by setting `initialModeId` to a temporary id in the request body. This is useful if you want to set values for variables in the mode in the `variableModeValues` array.
  - The `tempIdToRealId` array returns a mapping of the temporary ids in the request, to the real ids of the newly created objects.
- When adding new modes or variables, default variable values will be applied, consistent with what happens in the UI.
- Everything to be created, updated, and deleted in the request body is treated as one atomic operation. If there is any validation failure, you will get a 400 status code response, and no changes will be persisted.
- You will not be able to update remote variables or variable collections. You can only update variables in the file where they were originally created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to modify variables in. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_variables:write
