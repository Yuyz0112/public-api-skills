# PUT /rest/api/3/priorityscheme/{schemeId}

**Resource:** [Priority schemes](../resources/Priority-schemes.md)
**Update priority scheme**
**Operation ID:** `updatePriorityScheme`

Updates a priority scheme. This includes its details, the lists of priorities and projects in it

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | integer (int64) | Yes | The ID of the priority scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdatePrioritySchemeRequestBean](../schemas/Update/UpdatePrioritySchemeRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Returned if the request is accepted. |
| 400 | Returned if the request isn't valid.

**Mappings Validation Errors**

 *  ``The changes to priority schemes require mapping of priorities. Please provide a value for the 'in' mappings object.`` Priorities are being removed and/or projects are being added to the scheme, but ``in`` mappings are not provided.
 *  ``The changes to priority schemes require mapping of priorities. Please provide a value for the 'out' mappings object.`` Projects are being removed from the scheme, but ``out`` mappings are not provided.
 *  ``The priorities with IDs [ID 1, ID 2, ...] provided as keys for the 'in' mappings object do not exist. Please provide existing priority IDs.`` The listed priority ID(s) have been provided as keys for ``in`` mappings but do not exist. Please confirm the correct priority ID(s) have been provided, they should be priorities that exist on the Jira site which are used by projects being added to the current scheme, but are not in use by the current scheme.
 *  ``The priorities with IDs [ID 1, ID 2, ...] provided as values for the 'in' mappings object do not exist. Please provide existing priority IDs used by the current priority scheme.`` The listed priority ID(s) have been provided as values for ``in`` mappings but do not exist. Please confirm the correct priority ID(s) have been provided, they should be priorities that exist on the Jira site and are in use by the current scheme.
 *  ``The priorities with IDs [ID 1, ID 2, ...] provided as keys for the 'out' mappings object do not exist. Please provide existing priority IDs used by the current priority scheme.`` The listed priority ID(s) have been provided as keys for ``out`` mappings but are invalid. Please confirm the correct priority ID(s) have been provided, they should be priorities that exist on the Jira site and are in use by the current scheme.
 *  ``The priorities with IDs [ID 1, ID 2, ...] provided as values for the 'out' mappings object do not exist. Please provide existing priority IDs used by the default scheme.`` The listed priority ID(s) have been provided as values for ``out`` mappings but are invalid. Please confirm the correct priority ID(s) have been provided, they should be priorities that exist on the Jira site and are in use by the Default Priority Scheme, but are not in use by the current scheme.
 *  ``The priorities with IDs [ID 1, ID 2, ...] do not require mapping. Please remove these keys and their corresponding values from the 'in' mappings object.`` The listed priority ID(s) have been provided as keys for ``in`` mappings but are not required, they can be removed from the mappings object.
 *  ``The priorities with IDs [ID 1, ID 2, ...] require mapping. Please provide mappings in the 'in' mappings object, where these priorities are the keys with corresponding values.`` The listed priority ID(s) have not been provided as keys for ``in`` mappings but are required, add them to the mappings object.
 *  ``The priorities with IDs [ID 1, ID 2, ...] being mapped to are not in the current scheme. Please remove these values and their corresponding keys from the 'in' mappings object.`` The listed priority ID(s) have been provided as keys for ``in`` mappings but are not in use by the current scheme, they can be removed from the mappings object.
 *  ``The priorities with IDs [ID 1, ID 2, ...] do not require mapping. Please remove these keys and their corresponding values from the 'out' mappings object.`` The listed priority ID(s) hve been provided as keys for ``out`` mappings but are not required, they can be removed from the mappings object.
 *  ``The priorities with IDs [ID 1, ID 2, ...] require mapping. Please provide mappings in the 'out' mappings object, where these priorities are the keys with corresponding values.`` The listed priority ID(s) have not been provided as keys for ``out`` mappings but are required, add them to the mappings object.
 *  ``The priorities with IDs [ID 1, ID 2, ...] being mapped to are not in the default scheme. Please remove these values and their corresponding keys from the 'out' mappings object.`` The listed priority ID(s) have been provided as keys for ``out`` mappings but are not in use by the Default Priority Scheme, they can be removed from the mappings object. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permissions. |
| 409 | Returned if an action with this priority scheme is still in progress. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
