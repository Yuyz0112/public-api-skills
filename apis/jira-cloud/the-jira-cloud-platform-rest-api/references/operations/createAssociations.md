# PUT /rest/api/3/field/association

**Resource:** [Issue custom field associations](../resources/Issue-custom-field-associations.md)
**Create associations**
**Operation ID:** `createAssociations`

Associates fields with projects.

Fields will be associated with each issue type on the requested projects.

Fields will be associated with all projects that share the same field configuration which the provided projects are using. This means that while the field will be associated with the requested projects, it will also be associated with any other projects that share the same field configuration.

If a success response is returned it means that the field association has been created in any applicable contexts where it wasn't already present.

Up to 50 fields and up to 100 projects can be associated in a single request. If more fields or projects are provided a 400 response will be returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

Payload containing the fields to associate and the projects to associate them to.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [FieldAssociationsRequest](../schemas/Field/FieldAssociationsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the field association validation passes. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the field, project, or issue type is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
