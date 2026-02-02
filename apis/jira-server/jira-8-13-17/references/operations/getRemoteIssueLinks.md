# GET /issue/{issueIdOrKey}/remotelink

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `getRemoteIssueLinks`

A REST sub-resource representing the remote issue links on the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `globalId` | query | string | No | The id of the remote issue link to be returned.  If null (not provided) all remote links for the
                     issue are returned.
                     <p>For a fullexplanation of Issue Link fields please refer to
                     <a href="https://developer.atlassian.com/display/JIRADEV/Fields+in+Remote+Issue+Links">https://developer.atlassian.com/display/JIRADEV/Fields+in+Remote+Issue+Links</a></p> |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

