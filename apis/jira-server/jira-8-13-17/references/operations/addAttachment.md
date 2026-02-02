# POST /issue/{issueIdOrKey}/attachments

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `addAttachment`

Add one or more attachments to an issue.
 <p>
 This resource expects a multipart post. The media-type multipart/form-data is defined in RFC 1867. Most client
 libraries have classes that make dealing with multipart posts simple. For instance, in Java the Apache HTTP Components
 library provides a
 <a href="http://hc.apache.org/httpcomponents-client-ga/httpmime/apidocs/org/apache/http/entity/mime/MultipartEntity.html">MultiPartEntity</a>
 that makes it simple to submit a multipart POST.
 <p>
 In order to protect against XSRF attacks, because this method accepts multipart/form-data, it has XSRF protection
 on it.  This means you must submit a header of X-Atlassian-Token: no-check with the request, otherwise it will be
 blocked.
 <p>
 The name of the multipart/form-data parameter that contains attachments must be "file"
 <p>
 A simple example to upload a file called "myfile.txt" to issue REST-123:
 <pre>curl -D- -u admin:admin -X POST -H "X-Atlassian-Token: no-check" -F "file=@myfile.txt" http://myhost/rest/api/2/issue/TEST-123/attachments</pre>

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

