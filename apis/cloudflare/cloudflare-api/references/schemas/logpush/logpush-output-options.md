# logpush_output_options

The structured replacement for `logpull_options`. When including this field, the `logpull_option` field will be ignored.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `CVE-2021-44228` | boolean | No | If set to true, will cause all occurrences of `${` in the generated files to be replaced with `x{`. |
| `batch_prefix` | string | No | String to be prepended before each batch. |
| `batch_suffix` | string | No | String to be appended after each batch. |
| `field_delimiter` | string | No | String to join fields. This field be ignored when `record_template` is set. |
| `field_names` | string[] | No | List of field names to be included in the Logpush output. For the moment, there is no option to add all fields at once, so you must specify all the fields names you are interested in. |
| `output_type` | enum: ndjson, csv | No | Specifies the output type, such as `ndjson` or `csv`. This sets default values for the rest of the settings, depending on the chosen output type. Some formatting rules, like string quoting, are different between output types. |
| `record_delimiter` | string | No | String to be inserted in-between the records as separator. |
| `record_prefix` | string | No | String to be prepended before each record. |
| `record_suffix` | string | No | String to be appended after each record. |
| `record_template` | string | No | String to use as template for each record instead of the default json key value mapping. All fields used in the template must be present in `field_names` as well, otherwise they will end up as null. Format as a Go `text/template` without any standard functions, like conditionals, loops, sub-templates, etc. |
| `sample_rate` | number (float) | No | Floating number to specify sampling rate. Sampling is applied on top of filtering, and regardless of the current `sample_interval` of the data. |
| `timestamp_format` | enum: unixnano, unix, rfc3339 | No | String to specify the format for timestamps, such as `unixnano`, `unix`, or `rfc3339`. |

