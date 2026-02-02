# POST /issueLink

**Resource:** [issueLink](../resources/issueLink.md)
**Operation ID:** `linkIssues`

Creates an issue link between two issues.
 The user requires the link issue permission for the issue which will be linked to another issue.
 The specified link type in the request is used to create the link and will create a link from the first issue
 to the second issue using the outward description. It also create a link from the second issue to the first issue using the
 inward description of the issue link type.
 It will add the supplied comment to the first issue. The comment can have a restriction who can view it.
 If group is specified, only users of this group can view this comment, if roleLevel is specified only users who have the specified role can view this comment.
 The user who creates the issue link needs to belong to the specified group or have the specified role.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

