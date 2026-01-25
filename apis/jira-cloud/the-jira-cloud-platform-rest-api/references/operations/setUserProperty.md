# PUT /rest/api/3/user/properties/{propertyKey}

**Resource:** [User properties](../resources/User-properties.md)
**Set user property**
**Operation ID:** `setUserProperty`

Sets the value of a user's property. Use this resource to store custom data against a user.

Note: This operation does not access the [user properties](https://confluence.atlassian.com/x/8YxjL) created and maintained in Jira.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg), to set a property on any user.
 *  Access to Jira, to set a property on the calling user's record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `accountId` | query | string | No | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |
| `userKey` | query | string | No | This parameter is no longer available and will be removed from the documentation soon. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `username` | query | string | No | This parameter is no longer available and will be removed from the documentation soon. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `propertyKey` | path | string | Yes | The key of the user's property. The maximum length is 255 characters. |

## Request Body

The value of the property. The value has to be a valid, non-empty [JSON](https://tools.ietf.org/html/rfc4627) value. The maximum length of the property value is 32768 bytes.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the user property is updated. |
| 201 | Returned if the user property is created. |
| 400 | Returned if `accountId` is missing. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission or is not accessing their user record. |
| 404 | Returned if the user is not found. |
| 405 | Returned if the property key is not specified. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
