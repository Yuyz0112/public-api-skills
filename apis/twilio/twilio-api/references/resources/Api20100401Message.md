# Api20100401Message

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/2010-04-01/Accounts/{AccountSid}/Messages.json` | Retrieve a list of Message resources associated with a Twilio Account | [View](../operations/ListMessage.md) |
| POST | `/2010-04-01/Accounts/{AccountSid}/Messages.json` | Send a message | [View](../operations/CreateMessage.md) |
| GET | `/2010-04-01/Accounts/{AccountSid}/Messages/{Sid}.json` | Fetch a specific Message | [View](../operations/FetchMessage.md) |
| POST | `/2010-04-01/Accounts/{AccountSid}/Messages/{Sid}.json` | Update a Message resource (used to redact Message `body` text and to cancel not-yet-sent messages) | [View](../operations/UpdateMessage.md) |
| DELETE | `/2010-04-01/Accounts/{AccountSid}/Messages/{Sid}.json` | Deletes a Message resource from your account | [View](../operations/DeleteMessage.md) |
