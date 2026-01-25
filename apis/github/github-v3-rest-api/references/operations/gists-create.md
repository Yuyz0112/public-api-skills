# POST /gists

**Resource:** [gists](../resources/gists.md)
**Create a gist**
**Operation ID:** `gists/create`

Allows you to add a new gist with one or more files.

> [!NOTE]
> Don't name your files "gistfile" with a numerical suffix. This is the format of the automatic naming scheme that Gist uses internally.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[gist-simple](../schemas/gist-simple/gist-simple.md)

