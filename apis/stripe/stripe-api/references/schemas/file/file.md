# file

This object represents files hosted on Stripe's servers. You can upload
files with the [create file](https://api.stripe.com#create_file) request
(for example, when uploading dispute evidence). Stripe also
creates files independently (for example, the results of a [Sigma scheduled
query](#scheduled_queries)).

Related guide: [File upload guide](https://docs.stripe.com/file-upload)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `expires_at` | integer (unix-time) | No | The file expires and isn't available at this time in epoch seconds. |
| `filename` | string | No | The suitable name for saving the file to a filesystem. |
| `id` | string | Yes | Unique identifier for the object. |
| `links` | object | No | A list of [file links](https://api.stripe.com#file_links) that point at this file. |
| `object` | enum: file | Yes | String representing the object's type. Objects of the same type share the same value. |
| `purpose` | enum: account_requirement, additional_verification, business_icon... | Yes | The [purpose](https://docs.stripe.com/file-upload#uploading-a-file) of the uploaded file. |
| `size` | integer | Yes | The size of the file object in bytes. |
| `title` | string | No | A suitable title for the document. |
| `type` | string | No | The returned file type (for example, `csv`, `pdf`, `jpg`, or `png`). |
| `url` | string | No | Use your live secret API key to download the file from this URL. |

## Nested Fields

### `links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | file_link[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

