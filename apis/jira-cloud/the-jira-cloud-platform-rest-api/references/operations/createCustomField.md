# POST /rest/api/3/field

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Create custom field**
**Operation ID:** `createCustomField`

Creates a custom field.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

Definition of the custom field to be created

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CustomFieldDefinitionJsonBean](../schemas/Custom/CustomFieldDefinitionJsonBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the custom field is created. |
| 400 | Returned if:

 *  the user does not have permission to create custom fields.
 *  any of the request object properties have invalid or missing values. |

**Success Response Schema:**

[FieldDetails](../schemas/Field/FieldDetails.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
