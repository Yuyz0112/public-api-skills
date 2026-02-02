# GET /issue/{issueIdOrKey}

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `getIssue`

Returns a full representation of the issue for the given issue key.
 <p>
 An issue JSON consists of the issue key, a collection of fields,
 a link to the workflow transition sub-resource, and (optionally) the HTML rendered values of any fields that support it
 (e.g. if wiki syntax is enabled for the description or comments).
 <p>
 The <code>fields</code> param (which can be specified multiple times) gives a comma-separated list of fields
 to include in the response. This can be used to retrieve a subset of fields.
 A particular field can be excluded by prefixing it with a minus.
 <p>
 By default, all (<code>*all</code>) fields are returned in this get-issue resource. Note: the default is different
 when doing a jql search -- the default there is just navigable fields (<code>*navigable</code>).
 <ul>
 <li><code>*all</code> - include all fields</li>
 <li><code>*navigable</code> - include just navigable fields</li>
 <li><code>summary,comment</code> - include just the summary and comments</li>
 <li><code>-comment</code> - include everything except comments (the default is <code>*all</code> for get-issue)</li>
 <li><code>*all,-comment</code> - include everything except comments</li>
 </ul>
 <p>
 The {@code properties} param is similar to {@code fields} and specifies a comma-separated list of issue
 properties to include. Unlike {@code fields}, properties are not included by default. To include them all
 send {@code ?properties=*all}. You can also include only specified properties or exclude some properties
 with a minus (-) sign.
 <p>
 <ul>
 <li>{@code *all} - include all properties</li>
 <li>{@code *all, -prop1} - include all properties except {@code prop1} </li>
 <li>{@code prop1, prop1} - include {@code prop1} and {@code prop2} properties </li>
 </ul>
 </p>
 <p/>
 Jira will attempt to identify the issue by the <code>issueIdOrKey</code> path parameter. This can be an issue id,
 or an issue key. If the issue cannot be found via an exact match, Jira will also look for the issue in a case-insensitive way, or
 by looking to see if the issue was moved. In either of these cases, the request will proceed as normal (a 302 or other redirect
 will <b>not</b> be returned). The issue key contained in the response will indicate the current value of issue's key.
 <p/>
 The <code>expand</code> param is used to include, hidden by default, parts of response. This can be used to include:
 <ul>
 <li><code>renderedFields</code> - field values in HTML format</li>
 <li><code>names</code> - display name of each field</li>
 <li><code>schema</code> - schema for each field which describes a type of the field</li>
 <li><code>transitions</code> - all possible transitions for the given issue</li>
 <li><code>operations</code> - all possibles operations which may be applied on issue</li>
 <li><code>editmeta</code> - information about how each field may be edited. It contains field's schema as well.</li>
 <li><code>changelog</code> - history of all changes of the given issue</li>
 <li><code>versionedRepresentations</code> -
 REST representations of all fields. Some field may contain more recent versions. RESET representations are numbered.
 The greatest number always represents the most recent version. It is recommended that the most recent version is used.
 version for these fields which provide a more recent REST representation.
 After including <code>versionedRepresentations</code> "fields" field become hidden.</li>
 </ul>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fields` | query | string | No | the list of fields to return for the issue. By default, all fields are returned. |
| `expand` | query | string | No |  |
| `properties` | query | string | No | the list of properties to return for the issue. By default no properties are returned. |
| `updateHistory` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

