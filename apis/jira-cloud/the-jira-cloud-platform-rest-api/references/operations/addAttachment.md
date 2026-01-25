# POST /rest/api/3/issue/{issueIdOrKey}/attachments

**Resource:** [Issue attachments](../resources/Issue-attachments.md)
**Add attachment**
**Operation ID:** `addAttachment`

Adds one or more attachments to an issue. Attachments are posted as multipart/form-data ([RFC 1867](https://www.ietf.org/rfc/rfc1867.txt)).

Note that:

 *  The request must have a `X-Atlassian-Token: no-check` header, if not it is blocked. See [Special headers](#special-request-headers) for more information.
 *  The name of the multipart/form-data parameter that contains the attachments must be `file`.

The following examples upload a file called *myfile.txt* to the issue *TEST-123*:

#### curl ####

    curl --location --request POST 'https://your-domain.atlassian.net/rest/api/3/issue/TEST-123/attachments'
     -u 'email@example.com:<api_token>'
     -H 'X-Atlassian-Token: no-check'
     --form 'file=@"myfile.txt"'

#### Node.js ####

    // This code sample uses the 'node-fetch' and 'form-data' libraries:
     // https://www.npmjs.com/package/node-fetch
     // https://www.npmjs.com/package/form-data
     const fetch = require('node-fetch');
     const FormData = require('form-data');
     const fs = require('fs');
    
     const filePath = 'myfile.txt';
     const form = new FormData();
     const stats = fs.statSync(filePath);
     const fileSizeInBytes = stats.size;
     const fileStream = fs.createReadStream(filePath);
    
     form.append('file', fileStream, {knownLength: fileSizeInBytes});
    
     fetch('https://your-domain.atlassian.net/rest/api/3/issue/TEST-123/attachments', {
         method: 'POST',
         body: form,
         headers: {
             'Authorization': `Basic ${Buffer.from(
                 'email@example.com:'
             ).toString('base64')}`,
             'Accept': 'application/json',
             'X-Atlassian-Token': 'no-check'
         }
     })
         .then(response => {
             console.log(
                 `Response: ${response.status} ${response.statusText}`
             );
             return response.text();
         })
         .then(text => console.log(text))
         .catch(err => console.error(err));

#### Java ####

    // This code sample uses the  'Unirest' library:
     // http://unirest.io/java.html
     HttpResponse response = Unirest.post("https://your-domain.atlassian.net/rest/api/2/issue/{issueIdOrKey}/attachments")
             .basicAuth("email@example.com", "")
             .header("Accept", "application/json")
             .header("X-Atlassian-Token", "no-check")
             .field("file", new File("myfile.txt"))
             .asJson();
    
             System.out.println(response.getBody());

#### Python ####

    # This code sample uses the 'requests' library:
     # http://docs.python-requests.org
     import requests
     from requests.auth import HTTPBasicAuth
     import json
    
     url = "https://your-domain.atlassian.net/rest/api/2/issue/{issueIdOrKey}/attachments"
    
     auth = HTTPBasicAuth("email@example.com", "")
    
     headers = {
        "Accept": "application/json",
        "X-Atlassian-Token": "no-check"
     }
    
     response = requests.request(
        "POST",
        url,
        headers = headers,
        auth = auth,
        files = {
             "file": ("myfile.txt", open("myfile.txt","rb"), "application-type")
        }
     )
    
     print(json.dumps(json.loads(response.text), sort_keys=True, indent=4, separators=(",", ": ")))

#### PHP ####

    // This code sample uses the 'Unirest' library:
     // http://unirest.io/php.html
     Unirest\Request::auth('email@example.com', '');
    
     $headers = array(
       'Accept' => 'application/json',
       'X-Atlassian-Token' => 'no-check'
     );
    
     $parameters = array(
       'file' => File::add('myfile.txt')
     );
    
     $response = Unirest\Request::post(
       'https://your-domain.atlassian.net/rest/api/2/issue/{issueIdOrKey}/attachments',
       $headers,
       $parameters
     );
    
     var_dump($response)

#### Forge ####

    // This sample uses Atlassian Forge and the `form-data` library.
     // https://developer.atlassian.com/platform/forge/
     // https://www.npmjs.com/package/form-data
     import api from "@forge/api";
     import FormData from "form-data";
    
     const form = new FormData();
     form.append('file', fileStream, {knownLength: fileSizeInBytes});
    
     const response = await api.asApp().requestJira('/rest/api/2/issue/{issueIdOrKey}/attachments', {
         method: 'POST',
         body: form,
         headers: {
             'Accept': 'application/json',
             'X-Atlassian-Token': 'no-check'
         }
     });
    
     console.log(`Response: ${response.status} ${response.statusText}`);
     console.log(await response.json());

Tip: Use a client library. Many client libraries have classes for handling multipart POST operations. For example, in Java, the Apache HTTP Components library provides a [MultiPartEntity](http://hc.apache.org/httpcomponents-client-ga/httpmime/apidocs/org/apache/http/entity/mime/MultipartEntity.html) class for multipart POST operations.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** 

 *  *Browse Projects* and *Create attachments* [ project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue that attachments are added to. |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** Array of [MultipartFile](../schemas/Multipart/MultipartFile.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if any of the following is true:

 *  the issue is not found.
 *  the user does not have permission to view the issue. |
| 413 | Returned if any of the following is true:

 *  the attachments exceed the maximum attachment size for issues.
 *  more than 60 files are requested to be uploaded.
 *  the per-issue limit for attachments has been breached.

See [Configuring file attachments](https://confluence.atlassian.com/x/wIXKM) for details. |

**Success Response Schema:**

Array of [Attachment](../schemas/Attachment/Attachment.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
