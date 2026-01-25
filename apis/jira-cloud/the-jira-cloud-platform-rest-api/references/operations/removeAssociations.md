# DELETE /rest/api/3/field/association

**Resource:** [Issue custom field associations](../resources/Issue-custom-field-associations.md)
**Remove associations**
**Operation ID:** `removeAssociations`

Unassociates a set of fields with a project and issue type context.

Fields will be unassociated with all projects/issue types that share the same field configuration which the provided project and issue types are using. This means that while the field will be unassociated with the provided project and issue types, it will also be unassociated with any other projects and issue types that share the same field configuration.

If a success response is returned it means that the field association has been removed in any applicable contexts where it was present.

Up to 50 fields and up to 100 projects and issue types can be unassociated in a single request. If more fields or projects are provided a 400 response will be returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

Payload containing the fields to uassociate and the projects and issue types to unassociate them to.

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
