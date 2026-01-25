# GET /repos/{owner}/{repo}/languages

**Resource:** [repos](../resources/repos.md)
**List repository languages**
**Operation ID:** `repos/list-languages`

Lists languages for the specified repository. The value shown for each language is the number of bytes of code written in that language.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[language](../schemas/language/language.md)

