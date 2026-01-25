# logshare_timestamps

By default, timestamps in responses are returned as Unix nanosecond integers. The `?timestamps=` argument can be set to change the format in which response timestamps are returned. Possible values are: `unix`, `unixnano`, `rfc3339`. Note that `unix` and `unixnano` return timestamps as integers; `rfc3339` returns timestamps as strings.

**Type:** enum

## Values

- `unix`
- `unixnano`
- `rfc3339`
