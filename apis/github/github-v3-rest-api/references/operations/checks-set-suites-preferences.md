# PATCH /repos/{owner}/{repo}/check-suites/preferences

**Resource:** [checks](../resources/checks.md)
**Update repository preferences for check suites**
**Operation ID:** `checks/set-suites-preferences`

Changes the default automatic flow when creating check suites. By default, a check suite is automatically created each time code is pushed to a repository. When you disable the automatic creation of check suites, you can manually [Create a check suite](https://docs.github.com/rest/checks/suites#create-a-check-suite).
You must have admin permissions in the repository to set preferences for check suites.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[check-suite-preference](../schemas/check-suite-preference/check-suite-preference.md)

