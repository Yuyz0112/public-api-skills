# api.v2010.account.queue

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that this resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `current_size` | integer | No | The number of calls currently in the queue. |
| `friendly_name` | string | No | A string that you assigned to describe this resource. |
| `uri` | string | No | The URI of this resource, relative to `https://api.twilio.com`. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Queue resource. |
| `average_wait_time` | integer | No |  The average wait time in seconds of the members in this queue. This is calculated at the time of the request. |
| `sid` | string | No | The unique string that that we created to identify this Queue resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that this resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `max_size` | integer | No |  The maximum number of calls that can be in the queue. The default is 1000 and the maximum is 5000. |

